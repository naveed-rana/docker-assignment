# docker-assignment-01-PIAIC-Faisalabad

Assignment Requirement:
- Deploy any of application on any cloud
- Share your running application link (google form)

Assignment Help - Steps:
1- Download/clone running application from https://github.com/naveed-rana/docker-assignment (You can use any running application)
2- Create Dockerfile for the application.
3- Deploay it. (you can use free heroku account for deployment)

Above application details for dockerfile
1- Node.js application for serving portfolio files
How to run application:
2- you need linex env.
3- in your linex env, you should node.js installed
4- npm install (run this command on terminal for packages)
5- node server.js (run this command on terminal for application up and running)

Steps for free heroku deployment:
1- create heroku account
2- install heroku cli using > sudo snap install --classic heroku ( ref https://devcenter.heroku.com/articles/heroku-cli) 
3- heroku login (run this command on terminal for login)
4- open your terminal in assignment folder where your dockerfile exit.

Follow the left steps from (https://devcenter.heroku.com/articles/container-registry-and-runtime)
>heroku container:login
>heroku create yourapplicationname
(using this command you will get your domain like. https://naveedportfolio.herokuapp.com/)

>heroku container:push web
>heroku container:release web
>heroku open

Best of Luck! 
