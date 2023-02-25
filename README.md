<!-- Author: Emrah Kinay -->
<a name="readme-top"></a>
<div align="center">
  <a href="https://readshelf-web.herokuapp.com/">
        <h3 align="center">Active</h3>
        <p align="center">Drop-In Activities at City of Ottawa Recreation Facilities</p>
  </a>
</div>

## About The Project
Active is a mobile application that allows users to browse and search drop-in activities at City of Ottawa Recreation Facilities.

There is no API provided by the city for the drop-in activities and the data for the application is collected using Python web scraper and published using Spring Boot REST API Server on Docker.


Download the app on [AppStore](https://readshelf-web.herokuapp.com).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* Java
* Spring Boot
* Python
* MySQL
* REST API
* Docker
* Beautiful Soup

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Please follow the instructions below to get started with Active.

### Prerequisites
* Docker `20.10.20` Build `9fdeb9c`

### Installation
* Clone the repo
    ```sh
    git clone https://github.com/simulacrumus/active-docker
    ```
* Change your current directory
    ```sh
    cd Active-Docker
    ```
* Enter your keys in `.env` file
    ```conf
    MYSQL_DATABASE=<YOUR_DATABASE_NAME>
    MYSQL_USER=<YOUR_DATABASE_USERNAME>
    MYSQL_PASSWORD=<YOUR_DATABSE_USER_PASSWORD>
    MYSQL_ROOT_PASSWORD=<YOUR_DATABSE_ROOT_PASSWORD>
    MYSQL_PORT=<YOUR_DATABASE_PORT_NUMBER>
    SERVER_PORT=<YOUR_API_SERVER_PORT_NUMBER>
    API_KEY=<YOUR_API_KEY>
    TIME_ZONE=<YOUR_TIME_ZONE>
    ```
* Run Docker
    ```sh
   docker-compose up -d
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Emrah Kinay - [@emrahkinay](https://www.linkedin.com/in/emrahkinay/)

Project Link: [https://github.com/simulacrumus/active-docker](https://github.com/simulacrumus/active-docker)

AppStore Link: [https://readshelf-web.herokuapp.com](https://readshelf-web.herokuapp.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>