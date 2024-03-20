# online_home_rental_system
IT329 Advanced web Technologies

web-based using HTML, CSS, JS, ,AJAX, PHP, and MySQL

Your Home is the online home rental system, the front-end of the web application has been created, featuring user interfaces for both home seekers and homeowners. Now, the focus is on implementing the back-end functionality using PHP and a database. This involves creating and populating the necessary database tables for home seekers, homeowners, properties, and rent applications. The back-end functionalities include implementing secure login, logout, and signup features using sessions.

For home seekers, the back-end will facilitate viewing available properties, searching through them by category, applying to rent a property, and checking the status of previous applications. Homeowners, on the other hand, will be able to log in and out, list properties, view applications for their listed properties, and update application statuses. Additionally, a database will be designed and utilized to store and manage user data, property details, and rental applications.

To enhance the user experience, AJAX will be integrated into specific functionalities, making the web application more responsive and reducing the need for frequent page reloads. For instance, in the home seeker's home page, selecting a property category from the 'search by category' drop-down will trigger an AJAX call to a PHP page, which will return available properties within the selected category as JSON. The retrieved JSON data will then be used to dynamically update the 'Homes for Rent' table on the home seeker's page.

Similarly, for homeowners, AJAX will be implemented to handle actions such as accepting or declining rental applications and deleting listed properties. Clicking 'Accept' or 'Decline' buttons in the 'Rental Applications' table will initiate an AJAX call to a PHP page, updating the corresponding application status in the database based on the clicked button. The response from the PHP page will determine whether the status in the table should be updated.

the ER scheme is as follows:


<img width="508" alt="Screenshot 2024-03-21 010231" src="https://github.com/Futoon2002/online_home_rental_system/assets/101240944/dcbc7938-53a5-4c05-a9fb-9acf9c5ee5c6">
