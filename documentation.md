## Scanner App API Documentation

#### User Signup/Login

<details>
    <summary><code>POST</code> <code><b>/api/signup</b></code> <code>Adds user info and credentials to databse</code></summary>

##### Parameters

> | name        | type     | data type | description |
> | ----------- | -------- | --------- | ----------- |
> | `firstname` | required | string    | N/A         |
> | `lastname`  | required | string    | N/A         |
> | `email`     | required | string    | N/A         |
> | `password`  | required | string    | N/A         |

##### Responses

> | name       | type     | data type | description |
> | ---------- | -------- | --------- | ----------- |
> | `email`    | required | string    | N/A         |
> | `password` | required | string    | N/A         |
