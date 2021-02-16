# secret
A basic secret keeping web app with user authentication and encryption.
As I learn more about encryption and security, I add more branches containing higher and more secuer versions of the application.

## secret-v1
This version uses secret string from [mongoose-encryption](https://www.npmjs.com/package/mongoose-encryption). The secret is saved to a .env file and is loaded into the code using [dotenv](https://www.npmjs.com/package/dotenv). 

### Usage
To use this version, you need to create a .env file and define a secret string.

     touch .env
     vim .env
     
     SECRET=<putsecretstringhere>
