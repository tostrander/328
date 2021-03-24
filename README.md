# GRC Recipes

GRC Recipes is a web app built with the Fat Free Framework (F3) that allows users to submit their own recipes to the 
site. This web app was built for an assignment in SDEV 328 (Full Stack Web Development).

## Authors

- **Patrick D.** - Co-Founder/Developer
- **Ryan H.** - Co-Founder/Developer

## Built With

- [Fat Free Framework (F3)](https://fatfreeframework.com/3.7/home) - Used as the MVC.

## Installation

1. Ensure that [composer](https://getcomposer.org/) is installed on your server.
2. Modify the composer.json with your information.
3. Run the following command.
```bash
composer install
```
4. Modify the index.php, controller/, and model/ to suit your needs.

## Project REquirements

- [X] 1. Separates all database/business logic using the MVC pattern.
  - All database logic is located in model/
  - All HTML pages are located in views/
- [X] 2. Routes all URLs and leverages a templating language using the Fat-Free framework.
  - All routes are defined in index.php that call functions in controller/controller.php
- [X] 3. Has a clearly defined database layer using PDO and prepared statements. You should have at least two related tables.
  - All PDO and prepared statements are located in model/dataLayer.php
  - Navigate to misc-documents/ to see our .sql file for the database relations (all 6 are related).
- [X] 4. Data can be viewed and added.
  - User can sign up for an account, and can successfully log in (if they're an admin only right now).
  - There is a test account though to log in with:
    - Username: test
    - Password: Password01!
- [X] 5. Has a history of commits from both team members to a Git repository. Commits are clearly commented.
  - If you navigate to the commits page you will see 25 commits from Patrick and 32 from Ryan, at time of writing this.
- [X] 6. Uses OOP, and defines multiple classes, including at least one inheritance relationship.
  - We have a User, Validate, and DataLayer class. We don't have an inheritance relationship because we axed the "Admin" class we planned on doing.
  - User is located in classes/
  - Validate and DataLayer are located in model/
- [X] 7. Contains full Docblocks for all PHP files and follows PEAR standards.
  - Every PHP file has Docblocks and follows PEAR standards.
- [ ] 8. Has full validation on the client side through JavaScript and server side through PHP.
  - We don't have client side validation, only server side through PHP 😕 (model/validate.php).
- [X] 9. All code is clean, clear, and well-commented. DRY (Don't Repeat Yourself) is practiced.
  - Files were implemented with templating and F3's <loop>'s and <repeat>'s.
- [X] 10. Your submission shows adequate effort for a final project in a full-stack web development course.
  - I feel like it does? We both work full time + college so I feel like we didn't get as far as we could/other groups but it shows we at least picked up F3, PDO, and everything else we've learned in class.
- [ ] BONUS: Incorporates Ajax that access data from a JSON file, PHP script, or API. If you implement Ajax, be sure to describe it in your readme file.
  - There is NO ajax in this project.

