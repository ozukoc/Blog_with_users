<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ozukoc/blog_with_users">
    <img src="https://prnt.sc/CdxThx0S1ycM" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Blog Page</h3>

  <p align="center">
    with Users and Comments


    ·
    To Report a bug or request a feature you can mail me.

  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



I created this Blog-web-app while learning Flask. Within this project there are:

<li>User Registration/Login/Logout System</li>
<li>SQLAlchemy Relational Database</li>
<li>Secure hashed and also salted passwords</li>
<li>Users can create Blog Posts and comments.</li>

I used Jinja templates to make it more dynamic. And just to make it a little prettier I used Bootstrap in UI. Hope you like it!


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With


* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![Flask][Flask]][Flask-url]
* [![Python]][Python-url]
* [![SQLAlchemy][sqlalchemy.org]][sqlalchemy-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* install virtual environment package
  ```sh
  pip install virtualenv
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ozukoc/blog_with_users.git
   ```
3. Create virtual environment
   ```sh
   python -m virtualenv .
   .\scripts\activate
   ```
4. Install Required packages
   ```js
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You need to create your .env file and entera Secret Key, or you can paste this in main.py at 21st line.
```
SECRET_KEY = os.urandom(32)
app.config['SECRET_KEY'] = SECRET_KEY
```

After that you need to set set a DATABASE_URL variable in your .env file to show the adress of your Database or you can replace the  "uri" in "" app.config['SQLALCHEMY_DATABASE_URI'] = uri "" to  " 'sqlite:///blog.db' "

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@KocOzdes](https://twitter.com/KocOzdes) - ozdes24@gmail.com

Project Link: [https://github.com/ozukoc/blog_with_users](https://github.com/ozukoc/blog_with_users)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- MARKDOWN LINKS & IMAGES -->


[product-screenshot]: https://prnt.sc/CdxThx0S1ycM

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[Python]: https://img.shields.io/badge/-python-informational
[Python-url]:https://www.python.org/
[Flask]: https://img.shields.io/badge/-Flask-black
[Flask-url]:https://flask.palletsprojects.com/en/2.2.x/
[sqlalchemy.org]: https://img.shields.io/badge/-SqlAlchemy-red
[sqlalchemy-url]:https://www.sqlalchemy.org/
