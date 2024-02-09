<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<span id="top"></span>
<a name="readme-top"></a>
<h1 style="text-align:center; font-family: serif;">
    Yale Marketplace README
</h1>

<!-- PROJECT LOGO -->
<br />
<div style="text-align:center">
  <a href="https://www.dropbox.com/s/vf2cu32vegcg0yo/logo.png?dl=0">
    <img src="https://previews.dropbox.com/p/thumb/AB5FCdIbSo6832fW8bLkc25cEfPtpD8c3zaaaHukHa2-HUF-5QBdvH_dS-5Mb_qBdoTTDVlB-AfXJNcVMAKBmFeVjOMuhJypJpum26Uo1Va8K8fu3EVWLBEGpuqYBkeL49hAvMNIn_2axqDXJmbyP6RLT6_2sOCHt8GVZ5bcM1lBk_cL04P-yTNowiFBkJ2PzkyLWvMqT9sK-XrzCyVIIe39uqiv-8Q9kpw6ywzoxfdrYiSPGV707ofVsug_zgWpXz5wbSmdXHKkZXiEuD3d-JEUZ1yKUq0j0bwf7A6Sha9HaqUn6GUgtj_GiXkeioEUVGnG7ejflofmV7qd-dogD85M5yv7cAykgBFjGMZVNFJiwBan4xSzo6aZdGFElIEmNZQ/p.png" alt="Logo" width="250" height="250">
  </a>
</div>

<h3 style="text-align:center; font-family: serif;">Yale Marketplace</h3>

  <p style="text-align: center">
    One-stop solution for buying, selling, and renting within the Yale community!
    <br />
    </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Technology Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#testing">Testing</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

[![Yale Marketplace Screen Shot](https://previews.dropbox.com/p/thumb/AB4Z5sUmzREBGOuJ_EHqO5V3nugdcmji3G-Z5okE7HOvnNqpk0CrSY4DuKePm1orL1n56EDKLnDwRbOtn-6WIYu7YvCJ7KV-towZAeL9zqqYyCuXDXB7Mq1sWjKBljX7UxN-_CgGUMgAbNLNhlpr1Uc_BKnqUUHxMi8Lo41lgekGx745aUHIFuEYWV5kGsLMPpOL5zZmxCPfCmc7o0-p4GwRykTYuqVK-9q7SXV4jA54nr01sB--4rrky3Q0BPIhYo9SsmZ_ysYJgNrRT4hrN2q3THo9X66BfXNxiHwuU7fFXLD0LTPIVYTbU74R5QJoxdi2jCANWPn8NY1T4g3A2TvjNSDSu1d90Ofqv2SIJdPe3SygoAhzX4IT5AeCgBtP1nA/p.png)](https://github.com/yale-cpsc-419-sp23/project-project-group-9/tree/main)


Introducing **Yale Marketplace**, your one-stop solution for buying, selling, and renting within the Yale community! This platform is tailor-made for Yale students, faculty, and staff to easily trade items, bridging the gap between sellers and buyers on campus.

Explore a curated catalog of items, from textbooks to tech gadgets, while discovering great deals from your fellow Yalies. With our wishlist feature, keep track of all the times you're eyeing for future purchases, so you never miss out on a great find.

To ensure a safe and secure experience, Yale Marketplace employs Google OAuth 2.0 with `yale.edu` email validation, limiting access to verified members of the Yale community. Get ready to buy, sell, and connect like never before – join Yale Marketplace today!

[[Return to top]](#top)


### Technology Stack

* [![Flask][Flask-badge]][Flask-url]
* [![React][React.js]][React-url]
* [![Node.js][Node.js-badge]][Node.js-url]
* [![MySQL][MySQL-badge]][MySQL-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

[[Return to top]](#top)


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

#### 1. Node Package Manager `npm`
Type the following command in your terminal to install version `6.14.4` of the Node Package Manager, the version used by this project.
  ```sh
  npm install npm@6.14.4
  ```
Detailed instructions can be found [here](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm#checking-your-version-of-npm-and-nodejs).

> **Recommended**: On a related note, we recommend using NVM ([Node Version Manager](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/)) to switch between different versions of `Node.js` and install `npm`.

##### *Installing all node modules*

To install all necessary front-end modules, simply type the following command in your terminal:
  ```sh
  npm install 
  ```
  > **Note**: Ensure you are in the `/frontend` directory, otherwise the command won't work.
  

#### 2. MySQL

##### *Downloading MySQL*
1. Go to the [MySQL Community Downloads](https://dev.mysql.com/downloads/) page and select your operating system from the list of available options.
2. Select the appropriate MySQL Community Server edition and download the installer package for your operating system.
3. Follow the installation instructions to complete the installation of MySQL on your system.

##### *Creating a MySQL user*
1. Open the MySQL command-line client by typing the following command in your terminal:
    ```sh!
    mysql -u root -p 
    ```
    This will prompt you to enter the MySQL root user's password. Enter the password to log in to the MySQL server.    

2. Create a new MySQL user by typing the following command:
    ```sh!
    CREATE USER 'username'@'localhost' IDENTIFIED BY 'password'; 
    ```
    Replace username with the name you want to give to the new user and password with the password you want to assign to the user.

3. Exit the MySQL command-line client by typing ```exit;```

##### *Granting All Privileges to a MySQL User*
1. Log in to the MySQL command-line client by typing the following command in your terminal:
   ```sh!
    mysql -u root -p 
    ```
    This will prompt you to enter the MySQL root user's password. Enter the password to log in to the MySQL server.
    
2. Grant all privileges to the MySQL user by typing the following command:
   ```sh!
    GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost';
    ```
    Replace username with the name of the user you created in the previous section.

3. Exit the MySQL command-line client by typing ```exit;```


##### *Connecting to a MySQL Server from Terminal*
To connect to a MySQL server from the terminal, you can use the mysql command-line client. Here are the steps to connect to a MySQL server from the terminal:

1. Open the terminal on your system.

2. Type the following command to log in to the MySQL server:
      ```sh!
      mysql -u username -p
    ```
    
Replace username with the name of the MySQL user you created earlier.

This command will prompt you to enter the password for the MySQL user.

3. Enter the password for the MySQL user and press Enter.

If the password is correct, you will be logged in to the MySQL server and you will see the MySQL prompt, which looks like this: ```mysql>```


You can now execute SQL queries and perform other database operations directly from the MySQL prompt.

4. Exit the MySQL command-line client by typing ```exit;```
> [Optional Troubleshooting]: To test that your MySQL service is running type 
> ```ps -ef | grep mysql ``` into your terminal. 
> If you see a process with the name mysqld, it means that the MySQL service is running on your system.If you don't see a process with the name `mysql`, it means that the MySQL service is not running on your system.
> 
> Note that this only checks if the MySQL service is running and not whether you can connect to it. To test your MySQL connection, you should use the mysql command-line client or a testing tool specifically designed for that purpose.

    
### Installation

1. Download [Python 3.8.1](https://www.python.org/downloads/release/python-3810/), [Node.js, nvm, npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm#checking-your-version-of-npm-and-nodejs), and [MySQL 8.0.32](https://dev.mysql.com/doc/relnotes/mysql/8.0/en/news-8-0-32.html). 

3. Clone the repo
   ```sh
   git clone https://github.com/yale-cpsc-419-sp23/project-project-group-9.git
   ```
3. Install NPM packages 
   ```sh
   cd frontend
   npm install
   ```
   > Note: Ignore this step if done above
 
4. Install necessary `Flask/Python` modules:
All necessary modules are stored in `requirements.txt`. To install them, type the following in your terminal:
   ```sh
   pip install -r requirements.txt
   ```
   
### Running the application

1. Establish a MySQL connection
     ```sh
   mysql -u user_name -p
   ```
   > Enter the password when prompted.

2. Run the back-end server `/backend/server.py`
   ```sh
   cd backend
   python3.8 server.py
   ```

3. Run the front-end
   ```sh
   cd frontend
   npm start
   ```
   > **Recommended:** It is recommended to split the terminal before running the front-end so they can run simultaneously and all console output can be observed.

[[Return to top]](#top)

<!-- USAGE EXAMPLES -->
## Usage

### Key Features
1. ***Secure Authentication using Google OAuth 2.0***: Prevents non-Yale affiliates from logging into the marketplace.
2. ***Browse items on the Marketplace***: Users can search and browse items based on categories such as `Items`, `Renting`, `Services`. 
4. ***Add items to the wishlist***: Users can add items to their wishlist for future purchase or renting.
5. ***Get more information about the item***: Users can view detailed information about an items such as photos, description, price.
6. ***Contact the seller***: While the Marketplace does not intermediate transactions, Users can contact the seller directly to ask questions, negotiate prices, and arrange for pickup or delivery.
7. ***Filter/categorize searches***: Users can filter and categorize searches by various criteria such as `Date Posted`, `Price`, `Category.`
8. ***Create listings***: Users can create their own listings to sell or rent items to other users on the platform.
9. ***Update product listings***: Typed 'banana' instead of 'bandana' when posting your product? No problem! Users can freely access and update their listings (and their listings only!). 


<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->


<!-- Testing -->
## Testing

-  In the early stages of development, we conducted comprehensive unit testing on individual modules against their respective interface specifications. This approach allowed us to identify and resolve potential issues before they impacted the overall system, leading to a more robust and efficient final product.
-  Following the unit testing phase, we implemented integration testing to confirm that the various modules worked in perfect harmony. This crucial step allowed us to identify and address any conflicts or inconsistencies that may have arisen, ensuring seamless interaction between modules within the application.
-  Next, we performed extensive system testing by running the entire application and closely analyzing its performance under real-world conditions. This vital process allowed us to evaluate the Yale Marketplace's efficacy in meeting the requirements of Yale students and to confirm that their needs had been accurately interpreted and addressed by the application.
- During the final stages of our development process, we conducted a thorough Beta testing phase by inviting a diverse group of Yale students to interact with our application under close supervision. Since the application was not published, we provided them access to the Marketplace platform on our computers to simulate a real-world user experience. This hands-on approach allowed us to gather invaluable feedback directly from our target audience, helping us identify potential areas of improvement, identify other edge-cases and assess overall user satisfaction. By closely monitoring their interactions and listening to their suggestions, we were able to make necessary adjustments and fine-tune the Yale Marketplace application to better align with the needs and expectations of the Yale community. This collaborative effort with our end-users played a pivotal role in refining the application and making it more robust.

[[Return to top]](#top)


<!-- CONTRIBUTING -->
## Contributors

This is a group project for CPSC 419: Full Stack Web Programming. 
The following people have contributed to this project:

<li> Ananya Purushottam: ananya.purushottam@yale.edu </li>
<li> Neel Malhotra: neel.malhotra@yale.edu</li>
<li> Ali Hasnain: alihasnainbin.umer@yale.edu </li>
<li>Ron Pile: ron.pile@yale.edu </li>
<li>Juliet: juliet.otieno@yale.edu</li>
<br>

[[Return to top]](#top)


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
A heartfelt thank you to the following individuals for their invaluable support and guidance throughout the project:

* **Professor Alan Weide**: For his guidanc, support, and encouragement both in class and during office hours, which have been instrumental in the successful development of this project.
* **ULA Drew Beckman**: For his thoughtful guidance, constructive suggestions, and dedication to meeting with us every week to ensure the project was on track and progressing smoothly.
* **Udemy - [The Complete Web Development Bootcamp](https://www.udemy.com/course/full-stack-web-development-bootcamp)**: For extensive tutorials on `Flask`, `React`, and integrating the front-end and the back-end.
* **Codecacademy - [Create a Front-End App with React](https://www.codecademy.com/learn/paths/build-web-apps-with-react)**: For in-depth front-end tutorials and walkthroughs on building `React` components. 


We would also like to thank the entire teaching team whose hard work and dedication made this course an unforgettable learning experience. Thank you for carefully designing the problem-sets to not only help with this project, but also to slowly develop our knowledge of full-stack technologies. Thank you for a wonderful semester!


[[Return to top]](#top)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Flask-badge]: https://img.shields.io/badge/Flask-D00000?style=for-the-badge&logo=flask&logoColor=white
[Flask-url]: https://flask.palletsprojects.com/
[SQLAlchemy-badge]: https://img.shields.io/badge/SQLAlchemy-00A3D8?style=for-the-badge&logo=sqlalchemy&logoColor=white
[SQLAlchemy-url]: https://www.sqlalchemy.org/
[Node.js-badge]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
[Node.js-url]: https://nodejs.org
[MySQL-badge]: https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com


