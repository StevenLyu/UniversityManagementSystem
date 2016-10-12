# UniversityManagementSystem
A ASP.NET MVC project to manage all the information of a University


It’s a project to build a website to demonstrate and management all the information of a school, including students, teachers, departments and all the courses. All the information are stored in SQL-server database, users can get access and manage these data through the website interface. Code first strategy was used to build the whole project, so first the student class, teacher class, department class and course class were constructed, a dbcontext class was build to specify the model classes to build the database. After configure the connection string and add the initial data to the model, we can generate all the controllers and views using visual studio. At this time point, the website can run on web browsers. Users can search the data in the database, update and delete the informations through this website interface.

The third part account login like google account was implemented,  I use annotation to give authorization to different user, to make some of them administrator that have full authority to the database, where as others only can view the data, but can not update or delete the information. The concurrency problem was carefully take care by using time stamp. 
