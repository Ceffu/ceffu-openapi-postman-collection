This is a Postman collection of [Ceffu OpenAPI](https://apidoc.ceffu.io/apidoc/shared-c9ece2c6-3ab4-4667-bb7d-c527fb3dbf78/doc-338167)

First, download the repo and import both collection and environment files into postman.

Next, create an api key on [Ceffu](https://www.ceffu.com) platform. If you do not have an account, please reach to Ceffu at [here](https://www.ceffu.com/get-started)

Then fill in the values of "openapi" and "secret" of production environment according to the api key pair.

Common error code when calling api:

- G20005 Invalid parameter value

Required parameter is missing or value is invalid.

- G20010 Invalid API Key

API Key cannot be found or key status is not active. Check the information and status of api key from the platform.

- G20011 Invalid IP address

Source IP address is not in configured whitelist. Edit the IP whitelist of the api key and retry.

- G20013 No wallet permission

Wallet involved is not under your institution. Check `walletId` parameter and use string type to avoid number overflow

- G20015 Duplicated request

Request is considered to be duplicated because of same signature. This could happen if you are sending same request within a short period of time.

- G20016 No permission access this endpoint

The api key does not have the right permission to call the api. Check the required permission right from the documentation and edit the api key on the platform.

For more detail, please refer to [here](https://apidoc.ceffu.io/apidoc/shared-c9ece2c6-3ab4-4667-bb7d-c527fb3dbf78/doc-338174).
