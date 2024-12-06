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

### Disclaimer

Please be aware that using third-party software, such as Postman, to interact with this Postman collection may pose security risks. While we strive to ensure the safety and integrity of our resources, we cannot guarantee the security of third-party tools and services.

**Important Notice:**

- **Security Risks**: Using third-party software can expose your system and data to potential vulnerabilities, including but not limited to unauthorized access, data breaches, and malware.

- **User Responsibility**: It is your responsibility to ensure that your use of Postman and any other third-party software complies with your organization's security policies and best practices. You should take appropriate measures to safeguard your system and data.

- **No Liability**: We disclaim any liability for any security issues or damages that may arise from the use of third-party software in conjunction with this Postman collection. By using this collection, you acknowledge and accept these risks and agree to hold us harmless from any claims or damages resulting from such use.

We strongly recommend that you:

- Review and understand the security implications of using Postman or any other third-party software.
- Use secure and trusted environments when working with sensitive data.
- Regularly update your software to the latest versions to benefit from security patches and improvements.

By proceeding to use this Postman collection, you acknowledge that you have read, understood, and agreed to this disclaimer.
