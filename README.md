# Budget-App
> This is a mobile web application where you can manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.




  <p align="center">
    <a href="https://github.com/zairdon20/cochef-recipes#readme"><strong>Explore the docs ยป</strong></a>
    <br />
    <br />
    <a href="https://github.com/zairdon20/Expense-app">View Demo</a>
    ยท
    <a href="https://github.com/zairdon20/Expense-app/issues">Report Bug</a>
    ยท
    <a href="https://github.com/zairdon20/Expense-app/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
<summary align="center">Table of Contents</summary>

- [Budget-App](#budget-app)
  - [Description ๐๏ธ](#description-๏ธ)
    - [Prerequisites and Dependencies ๐](#prerequisites-and-dependencies-)
    - [Setup](#setup)
      - [Setting Up PostgreSQL](#setting-up-postgresql)
    - [Clone this repository](#clone-this-repository)
    - [Move into the directory with](#move-into-the-directory-with)
    - [Install linter](#install-linter)
    - [Install Bootstrap and it's dependencies](#install-bootstrap-and-its-dependencies)
    - [Create the database](#create-the-database)
    - [Install linter](#install-linter-1)
    - [Run linter](#run-linter)
      - [Auto-correct](#auto-correct)
    - [Run Project](#run-project)
  - [Built With ๐จ](#built-with-)
  - [Authors โ๏ธ](#authors-๏ธ)
  - [๐ค Contributors](#-contributors)
  - [๐ License](#-license)
  - [Show your support ๐ช](#show-your-support-)
  - [Acknowledgments](#acknowledgments)
</details>

## Description ๐๏ธ
### Prerequisites and Dependencies ๐

You will be needing:

- A terminal terminal
- A code editor
- Ruby (follow the instructions based on your OS)
  ```bash
  https://www.ruby-lang.org/en/documentation/installation/
  ```
- Rails (follow the instructions based on your OS)
    ```bash
    https://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project-installing-rails
    ```

- Postgresql (follow the instructions based on your OS)
  ```bash
  https://www.postgresql.org/download/
  ```
- Bootstrap and it's dependencies including jquery and popper.js.
- - [Heroku Deploy](https://clinton-budget-app.herokuapp.com/)


### Setup

#### Setting Up PostgreSQL

- The postgres installation doesn't setup a user for you, so you'll need to follow these steps to create a user with permission to create databases

  ```bash
  sudo -u postgres createuser <Username> -s
  ```

### Clone this repository

```bash
git clone https://github.com/zairdon20/Budget-app.git
```
### Move into the directory with

  ```bash
  cd Budget-app
  ```

### Install linter

  ```bash
  bundle install
  ```
### Install Bootstrap and it's dependencies

```bash
yarn add bootstrap jquery popper.js
```

### Create the database
You don't need to run this command unless you want to use a seperate database.

```bash
rails db:create
```
<div align="center">OR</div>

```bash
rake db:create
```

### Install linter

For Ruby and Rails run:
  ```bash
  bundle install
  ```

For stylelint:

  ```bash
  npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
  ```

### Run linter
For Ruby
```bash
rubocop .
```
For Stylelint:
```bash
npx stylelint "**/*.{css,scss}"
```

#### Auto-correct

In auto-correct mode, RuboCop and stylelint will try to automatically fix offenses:

For rubocop:
```bash
rubocop -A
```
 **<div align=center>OR</div>**

```bash
rubocop --auto-correct-all
```

For stylelint:

```bash
npx stylelint "**/*.{css,scss}" --fix
```
### Run Project
```bash
rails s
```
<div align="center">OR</div>

```bash
rails server 
```
This will start a server at:
```bash
localhost:3000
```
You can paste or type it on url bar

<p align="right">(<a href="#top">back to top</a>)</p>
  
<p align="right">(<a href="#top">back to top</a>)</p>

## Built With ๐จ
<div align="center">

|| Languages ||
|-|-------------|-|
||![Ruby](https://img.shields.io/badge/-Ruby-000000?style=flat&logo=ruby&logoColor=red)![Ruby on Rails](https://img.shields.io/badge/-Ruby_on_Rails-000000?style=flat&logo=ruby-on-rails&logoColor=blue)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
||

</div>

<div align="center">

||Tools ๐?๏ธ||
|-|-------------|-|
||![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)   ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)  ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)||
<p align="right">(<a href="#top">back to top</a>)</p>
</div>

## Authors โ๏ธ
<div align="center">


<p align="right">(<a href="#top">back to top</a>)</p>


| ๐ค Josphat Nkonde |
|---|
|<a target="_blank" href="https://github.com/zairdon20"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Github profile"></a>  <a target="_blank" href="https://www.linkedin.com/in/fob90s"><img src="https://img.shields.io/badge/-LinkedIn-0077b5?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="Linkedin profile"></a> <a target="_blank" href="https://twitter.com/fob90s"><img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=Twitter&logoColor=white" alt="Twitter profile"></a>  
<a target="_blank" href="mailto:josphat2020.com"><img src="https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=Gmail&logoColor=white" alt="Gmail account"></a> <a target="_blank" href="https://wa.me/+2349066478370"> <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Whatsapp account">+260961546786</a> 
(Click any of the badges to reach me. Especially whatsapp)|
</div>

<p align="right">(<a href="#top">back to top</a>)</p>


## ๐ค Contributors

Contributions, issues, and feature requests are greatly appreciated!

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "improvements or suggestions".

- Fork the Project
- Create your Feature Branch (git checkout -b feature/yourfeaturename)
- Commit your Changes (git commit -m 'Add suggested feature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

Feel free to check the [issues page](https://github.com/fobadara/cochef-recipes/issues).

<p align="right">(<a href="#top">back to top</a>)</p>

## ๐ License

This project is licensed by [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./MIT.md)

## Show your support ๐ช
Give a โญ๏ธ if you like this project or buy me a coffee!

## Acknowledgments

- Hat tip to anyone whose code was used.
  

<p align="right">(<a href="#top">back to top</a>)</p>
