# secret
A basic secret keeping web app with user authentication and encryption.
As I learn more about encryption and security, I add more branches containing higher and more secuer versions of the application.

## secret-v3
In this version the md5 was replaced by [bcypt](https://www.npmjs.com/package/bcrypt) package to hash the password.
salt rounds have been set to 10.

          const saltRounds = 10;  
