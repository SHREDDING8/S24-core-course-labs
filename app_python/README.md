# Python web application

[![App python](https://github.com/SHREDDING8/S24-core-course-labs/actions/workflows/app_python.yml/badge.svg)](https://github.com/SHREDDING8/S24-core-course-labs/actions/workflows/app_python.yml)


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">DevOps course labs</h3>
  <p align="center">
    An application developed within Innopolis Univeristy "DevOps Engineering" course
    <br />
    <a href="https://github.com/SHREDDING8/S24-core-course-labs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SHREDDING8/S24-core-course-labs">View Demo</a>
    ·
    <a href="https://github.com/SHREDDING8/S24-core-course-labs/issues">Report Bug</a>
    ·
    <a href="https://github.com/SHREDDING8/S24-core-course-labs/issues">Request Feature</a>
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
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Web application developed using best practices of production development.

Includes:

* DevOps tasks
* Backend tasks

### Built With

Framework used:

* ![FastAPI][FastAPI]

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Required software:

* python 3.9

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/SHREDDING8/S24-core-course-labs.git
   ```

2. Install python packages

   ```sh
   pip install -r requirements.txt
   ```

3. Enter your variables in *.env files. The project has an example.env file

### Unit Tests
```shell
pytest tests/
```

### Docker

* How to build

```shell
docker build -t server-app .
```

* How to pull

```shell
docker pull shredding228/server_app:latest 
```

* How to run

```shell
docker run -d -p 8080:8080 --name app_python server-app:latest 
```

## CI workflow:
1. Set up python 3.9
2. Creating env file, installing dependencies 
3. Linting (flake8 linter is used)
4. Tests (pytest is used)
5. Login to DockerHub, build image and push 

<!-- USAGE EXAMPLES -->
## Usage

To view current Moscow time open http://{host}:{port}/moscow-time

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->
## Contact

Anatoliy Shvarts - a.shvarts@innopolis.university

Project Link: [https://github.com/SHREDDING8/S24-core-course-labs](https://github.com/SHREDDING8/S24-core-course-labs)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Innopolis University](https://innopolis.university/)
* [Img Shields](https://shields.io)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[FastAPI]: https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white