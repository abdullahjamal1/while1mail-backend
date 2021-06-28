# while1mail-backend
### frontend of this application => [https://github.com/aj941ga/while1mail-frontend](https://github.com/aj941ga/while1mail-frontend)

 ________________________________________________________________________________________________________
 ## Features supported
 
 - [x] supports all general mail features
 - [x] supports recurring, weekly, monthly and yearly scheduling features
 - [x] supports rich text editor (bold, italic, colour, font etc)
 - [x] developed using MERN stack
 - [x] Login and Sign up via username, password and google
 - [x] Create/Edit the mail features.
 - [x] home page to show scheduled mails and history page to show mail log
 ________________________________________________________________________________________________________

To clone and install the application on linux
```shell
$ git clone https://github.com/aj941ga/while1mail-backend.git
$ cd while1mail-backend
$ mpm install
```
Then set values for environment variables ( check \config )
```shell
 export while1mail_jwtPrivateKey=********
 export while1mail_mail_verification_key=********
 export while1mail_email=*********
 export while1mail_gmail_pass=*********
 export while1mail_google_clientId=********
 export while1mail_google_client_secret=*******
 export while1mail_mongodb_url=********
```
To run the application
```shell
$ npm start
```
