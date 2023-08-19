# portfolio
A list of deployed personal projects. WIP!

## Art portfolio website
A web app for showcasing personal art work, built using Vue.js and Node.js and deployed on firebase.
Still in preliminary stages, planning to add an express backend to communicate with a postgreSQL database of urls for cloud-hosted images. This should prevent the frontend app becoming overburdened with large images.
Functioning contact feature on the landing page.

*Originally deployed to github-pages but moved to firebase due to caching issues* 

**Find it here:** [https://artsite-e1dd0.firebaseapp.com/#/](https://artsite-e1dd0.firebaseapp.com/#/)

![artsite landing page](https://github.com/TortoiseLeaf/portfolio/blob/main/img/artsite.png?raw=true)

**Tech stack:**

![vue.js](https://github.com/TortoiseLeaf/portfolio/blob/main/img/vuejs.png) ![node.js](https://github.com/TortoiseLeaf/portfolio/blob/main/img/nodejs.png) ![firebase](https://github.com/TortoiseLeaf/portfolio/blob/main/img/firebase.png) ![bootstrap](https://github.com/TortoiseLeaf/portfolio/blob/main/img/bootstrap.png?raw=true)

---------------------------


## Slack Chatbot

Following an IBM tutorial [here](https://cloud.ibm.com/docs/solution-tutorials?topic=solution-tutorials-slack-chatbot-database-watson#slack-chatbot-database-watson). **_(Resources are since deleted to avoid accruing charges.)_**

- Using the IBM cloud cli to create a DB2 instance and a Code Engine app to serve it. This app serves as a backend allowing the database to communicate with an IBM Watson Assistant chatbot on the frontend. 
- The Watson Assistant connects to the tutorial source code by uploading an `openapi-spec.json` in-browser, allowing access to database CRUD functions in `app.py`. 
- In-browser web Actions are then created from scratch to handle user input and to read and write to and from the database. 
- The chatbot app is then integrated to a Slack app deployed to a workspace.

[Deployed on Slack example:](https://vimeo.com/855946976?share=copy)

[Deployed on Web example:](https://vimeo.com/855950454?share=copy)


**Tech stack:**

![ibmcloud](https://github.com/TortoiseLeaf/portfolio/blob/main/img/ibmcloud-trsp.png) 
![watson-ai](https://github.com/TortoiseLeaf/portfolio/blob/main/img/watson.png?raw=true)
![python](https://github.com/TortoiseLeaf/portfolio/blob/main/img/python.png?raw=true) 
![Slack](https://github.com/TortoiseLeaf/portfolio/blob/main/img/slack.png?raw=true)

-----------------------------------------







