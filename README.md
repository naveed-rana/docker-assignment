# docker-assignment-01-PIAIC-Faisalabad

Assignment Requirement:
- Deploy any of application on any cloud
- Share your running application link https://docs.google.com/forms/d/e/1FAIpQLSeGm00nVuw_YUt3S5a6f48YN3mxZlUQiKci2yQlMON3LC_KTQ/viewform?usp=sf_link(google form)
<br/>
Assignment Help - Steps:
1- Download/clone running application from https://github.com/naveed-rana/docker-assignment (You can use any running application)
<br/>
2- Create Dockerfile for the application.<br/>
3- Deploay it. (you can use free heroku account for deployment)<br/>

Above application details for dockerfile<br/>
1- Node.js application for serving portfolio files<br/>
How to run application:<br/>
2- you need linux env.<br/>
3- in your linux env, you should node.js installed<br/>
4- npm install (run this command on terminal for packages)<br/>
5- node server.js (run this command on terminal for application up and running)<br/>
6- Internal application Port 5000<br/>

Steps for free heroku deployment:<br/>
1- create heroku account<br/>
2- install heroku cli using > sudo snap install --classic heroku ( ref https://devcenter.heroku.com/articles/heroku-cli) <br/>
3- heroku login (run this command on terminal for login)<br/>
4- open your terminal in assignment folder where your dockerfile exit.<br/>

Follow the left steps from (https://devcenter.heroku.com/articles/container-registry-and-runtime)<br/>
>heroku container:login<br/>
>heroku create yourapplicationname<br/>
(using this command you will get your domain like. https://naveedportfolio.herokuapp.com/)<br/>

>heroku container:push web<br/>
>heroku container:release web<br/>
>heroku open<br/>

Best of Luck! 
