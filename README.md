# Portfolio
#### Video Demo:  <https://www.youtube.com/watch?v=pGhn7y1IWLY>
#### Description:
For the final project, I decided to create a web portfolio where I will present my most important projects to date in order to demonstrate my skills. I will make the website using the technologies covered in the CS50 course, such as Flask, SQLite, Python, HTML, CSS, and Bootstrap.

The first thing I did was install the necessary technologies on my computer to use them in the local Visual Studio Code editor. I installed the Flask framework to start working on my project. Then, I created the database, which consists of the users table, the projects table, and the contact table.

Once the database was set up, I continued by creating all the routes for my portfolio, two routes to display my portfolio and seven routes for the dashboard, which allows me to create and view records in the database. My next step was to create the interfaces for each route, and then implement the functionalities that each required.

I started with the dashboard routes, ensuring that each route is only accessible if the user is logged in. I added functionality for login, logout, the records route to view records from the projects and contact tables, and functionalities to add a user. The project creation route was the one that gave me the most trouble because I wasn’t sure how to handle images and videos for storing them in the database. In the first version, I saved the image and video inside the project files, then converted them into a Blob to store them in the database. In the final version, I saved the image and video inside the project files and stored their paths in the database.

For the portfolio routes, there’s the projects route that contains all the information for each project, and the About Me route where I provide my information and various ways to contact me like email or fill a form in the route to leave me a message, also on the footer of the page there’s a link to access my LinkedIn and a GitHub link to access the code of all the projects presented and this portfolio. To style the website I used Bootstrap to make it responsive and CSS to add my personal touches.
