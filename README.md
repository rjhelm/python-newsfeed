<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/rjhelm/python-newsfeed">
    <img src="https://github.com/rjhelm/python-newsfeed/blob/main/assets/home.png?raw=true" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Python Tech News Discussion Board</h3>

  <p align="center">
    Discussion board web application built with python and templating. 
    <br />
    <a href="https://github.com/rjhelm/python-newsfeed"><strong>See the code</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Python News][home-page]](https://github.com/rjhelm/python-newsfeed/blob/main/assets/home.png?raw=true)

This is a discussion board web application the has been refactored. Originally built using Node.js and express, now refactored to utilize a python backend and templating that python is compatible with as well.

How it works:

* Using a virtual enviornment calls are made to dependencies needed to create a functioning python backend. 
* Using templating and routes created through flask allows the user to navigate the web app.
* Using my MySQL along with sqlalchemy we are able to create models and a schema for storing user data.
* Authentication for login, signup, logout. Also bcrypt for password hashing and securing user passwords.

We were able to replace the use of node, express, sequelize and jwt with python and create a functioning web application.

[![Python News][login-signup]](https://github.com/rjhelm/python-newsfeed/blob/main/assets/login-signup.png?raw=true)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

Created using:

* [Python](https://www.python.org//)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [MySQL](https://www.mysql.com/)
* [Sqlalchemy](https://www.sqlalchemy.org/)
* [PyMySQL](https://pymysql.readthedocs.io/en/latest/)
* [bcrypt](https://pypi.org/project/bcrypt/)
* [python-dotenv](https://pypi.org/project/python-dotenv/)
* [Gunicorn](https://docs.gunicorn.org/en/stable/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Deploy 
- [x] Add ability to signup, login, logout
- [] Add ability to post images
- [] Styling changes
- [] Use different frontend 
    - [] N/A
    - [] N/A

See the [open issues](https://github.com/rjhelm/python-newsfeed) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Any contributions are welcome.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/your-feature`)
3. Commit your Changes (`git commit -m 'Add your feature'`)
4. Push to the Branch (`git push origin feature/your-feature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License



<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Ryan Helm - [@ryan_j_dev](https://twitter.com/ryan_j_dev) - ryjhelm@gmail.com

Project Link: [https://github.com/rjhelm/python-newsfeed](https://github.com/rjhelm/python-newsfeed)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rjhelm/python-newsfeed.svg?style=for-the-badge
[contributors-url]: https://github.com/rjhelm/python-newsfeed
[issues-shield]: https://img.shields.io/github/issues/rjhelm/python-newsfeed.svg?style=for-the-badge
[issues-url]: https://github.com/rjhelm/python-newsfeed/issues
[license-shield]: https://img.shields.io/github/license/rjhelm/python-newsfeed.svg?style=for-the-badge
[license-url]: https://github.com/rjhelm/python-newsfeed/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/ryjhelm
