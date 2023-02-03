## Scanner App API Documentation

#### User Signup/Login

<details>
    <summary><code>POST</code> <code><b>/api/signup</b></code> <code>Adds user info and credentials to database</code></summary>

##### Parameters

> | name        | type     | data type | description |
> | ----------- | -------- | --------- | ----------- |
> | `firstname` | required | string    | N/A         |
> | `lastname`  | required | string    | N/A         |
> | `email`     | required | string    | N/A         |
> | `password`  | required | string    | N/A         |

##### Responses

> | http code | content-type       | response                                            |
> | --------- | ------------------ | --------------------------------------------------- |
> | `201`     | `application/json` | `{"message":"User successfully created"}`           |
> | `400`     | `application/json` | `{"message":"Error decoding JSON body"}`            |
> | `400`     | `application/json` | `{"message":"Email not registered to any account"}` |
> | `500`     | `application/json` | `{"message":"Could not generate password hash"}`    |

</details>

<details>
    <summary><code>POST</code> <code><b>/api/login</b></code> <code>Authenticates and saves cookie to be used by frontend</code></summary>

##### Parameters

> | name       | type     | data type | description |
> | ---------- | -------- | --------- | ----------- |
> | `email`    | required | string    | N/A         |
> | `password` | required | string    | N/A         |

</details>
