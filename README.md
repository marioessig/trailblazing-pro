# Trailblazing Pro

As an avid Salesforce enthuastist, I want to create a place where we can share posts, vote and comment all things Salesforce. Let's grow together and continue to spread the well-known Ohana culture here!

Visit the Heroku-based* website: [Trailblazing Pro](https://geekpanda-trailblazingpro.herokuapp.com/)

_*This is made possible with [Heroku](https://www.heroku.com/) with [JASWSDB MySQL](https://elements.heroku.com/addons/jawsdb) add-on installed._

---

*Tip: install these packages via terminal in the root directory to be able to use this application:* <br>

**NPM** <br>
`npm init` <br>

**MySQL** <br>
`npm i --save mysql2` <br>

**dotenv** <br>
`npm i dotenv --save` <br>

**bcrypt** <br>
`npm i bcrypt` <br>

**express** <br>
`npm i express` <br>

**express-handlebars** <br>
`npm i express-handlebars` <br>

**express-session** <br>
`npm i express-session` <br>

**Sequelize** <br>
`npm i sequelize` <br>

**connect-session-sequelize** <br>
`npm i connect-session-sequelize` <br>

**Want to install all at once?** <br>
`npm init -y` first then enter the next code:
`npm i mysql2 dotenv bcrypt express express-handlebars express-session sequelize connect-session-sequelize`

Then update the **package.json** file with: `"start": "node server.js"`

### Using the program
Make sure to follow the instructions below to use the database:
1. In the terminal in the root directory, start MySQL: `mysql -u root -p` and enter your MySQL password
2. Create database tables: `source db/schema.sql`
3. Quit MySQL: `quit`
4. Seed tables with data: `npm run seed`
5. Start the program: `node server.js`
6. Use Insomnia Core App and "http://localhost:3001" and have fun playing around with it!