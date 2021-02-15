# aws-cognito-http
AWS Cognito with http only cookie.


# Installation
npm install --save
npm run dev

# Setup Cognito
## Instalation steps 
### 1. Create AWS account and go to the Cognito settings
### 2. Click Manage User Pools
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/1.png)
### 3. Type pool name and click Step through settings
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/2.png)
### 4. In the attributes tab check the options as below and click next
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/3.png)
### 5. In the policies tab select as below
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/4.png)
### 6. Next in the MFA tab select as below
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/5.png)
### 7. Then in the App clients tab add an app client
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/6.png)
### 8. Afterwards check as below
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/7.png)
### 9. Next two steps you can skip and finally you will see some thing like this
![](https://github.com/cnikolov/aws-cognito-http/blob/main/assets/8.png)
### 10. Create .env file and save your Pool Id, App client id and Pool region
#### .env file in the root folder

# Try it out with Postman
Import the profile in postman and test on your own pace.

# Special Credits
ja-klaudiusz who originally wrote the solution to work with nuxt.
