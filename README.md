<h1>A Blog Website with user registration and commenting/posting system</h1>

<h3>Backend: Flask and SQLAlchemy relational database and Jinja2 Dynamic Templating</h3>
<h3>Frontend: Simple Bootstrap</h3>


<h5>I made this project while learning flask and sql with a Udemy course. So for the frontend, there is simple bootstrap with simple text.</h5>

You can register users. Login/Logout and comment on posts with the logged in user account. All user passwords are encrypted and then added to database.<br>
Right now you can only make posts with the first registered user account.(I call it admin account,since this is a personal blog website I think it makes sense.)<br>All the posts and comments are added to database.<br><br>This can be used as a template for any blog website. Just change the html and css and It is good to go. Hope you'll like it. =)

You can see the live version on <a href="https://koc-blog.onrender.com/"> Here</a>
I deployed it on render and used Postgresql for database. I added postgresql database information to the environment variables on render.com so if you want to run the database localy, <br> you can replace the  "uri" in "" app.config['SQLALCHEMY_DATABASE_URI'] = uri "" to  " 'sqlite:///blog.db' "
