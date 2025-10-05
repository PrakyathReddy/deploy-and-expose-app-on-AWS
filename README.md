# Deploying a Node Js Application on AWS EC2

### Testing the project locally

1. Clone this nodejs app code
git clone https://github.com/verma-kunal/AWS-Session.git

2. Setup the following environment variables - `(.env)` file
DOMAIN= "http://localhost:3000"
PORT=3000
STATIC_DIR="./client

3. Initialise and start the project
npm install
npm run start

### deploy to AWS and expose 

4. login to console > IAM > create users > provide username and custom password > attach IAM policies > Administrator Access

5. Sign out and sign in using the newly created IAM user

6. Launch an EC2 instance and ssh into it

7. On the ec2 instance, install npm & nodejs, clone repo, update .env variables, npm install, npm run start

8. Application now running successfully on ec2 instance localhost