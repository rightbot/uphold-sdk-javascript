# `.updateMe()`

Updates the authenticated user's details.

The `otp` argument will add the `OTP-TOKEN` header to the request.

| Argument  | Type   | Required | Description                                              |
|:----------|:-------|:---------|:---------------------------------------------------------|
| `body`    | Object | Yes      | Request body                                             |
| `otp`     | String | No       | OTP token                                                |
| `options` | Object | No       | Any options you may want to pass to [`.api()`](/sdk#api) |

The `body` argument accepts the following keys:

| Key         | Type   | Description          |
|:------------|:-------|:---------------------|
| `address`   | Object | Address details      |
| `birthdate` | String | Birthdate            |
| `country`   | String | Country of residence |
| `firstName` | String | First name           |
| `identity`  | Object | Identity details     |
| `lastName`  | String | Last name            |
| `settings`  | Object | Settings details     |
| `state`     | String | Country state        |
| `username`  | String | Username             |

This method returns a **Promise**.
