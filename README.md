# Express Boilerplate

For starting new Node/Express projects more quickly with a foundation.

![express](https://camo.githubusercontent.com/0a95585d6b3a07028298a45d60b85a1331358bc336549d64dbbc27977f1495f3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d4578707265737326636f6c6f723d303030303030266c6f676f3d45787072657373266c6f676f436f6c6f723d464646464646266c6162656c3d)
![node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![mocha](https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&logo=Mocha&logoColor=white)
![heroku](https://camo.githubusercontent.com/19764c8c39927763a01a6468b533a874ecc23d80143f9ae260eec76b696c7d82/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d4865726f6b7526636f6c6f723d343330303938266c6f676f3d4865726f6b75266c6f676f436f6c6f723d464646464646266c6162656c3d)

## Set up

Complete the following steps to start a new project (NEWPROJECT-NAME):

1. Clone this repository to your local machine `git clone https://github.com/CodeLikeAGirl29/express-boilerplate NEW-PROJECTS-NAME`
2. `cd` into the cloned repository
3. Make a fresh start of the git history for this project with
   `rm -rf .git && git init`
4. Install the node dependencies `npm install`
5. Move the example Environment file to `.env` that will be
   ignored by git and read by the express server `mv example.env .env`
6. Edit the contents of the `package.json` to use NEW-PROJECTNAME instead of `"name": "express-boilerplate",`

## Scripts

Start the application `npm start`
Start nodemon for the application `npm run dev`
Run the tests `npm test`

## Deploying

When your new project is ready for deployment, add a new Heroku
application with `heroku create`. This will make a new git
remote called "heroku" and you can then `npm run deploy` which
will push to this remote's main branch.
