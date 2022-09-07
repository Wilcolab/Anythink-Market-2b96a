# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
* Download the [Docker](https://docs.docker.com/get-docker/) as per your OS
  * :heavy_exclamation_mark: Don't forget to read the system requirements
  * In windows, if you are downloading from WSL 2 Backend, then you must download WSL. Download from [here](https://docs.microsoft.com/en-us/windows/wsl/install-on-server)
* After downloading, run the setup. It'll take some time to complete

## Run Docker
* Then, simply run the docker and make sure that it is running perfectly fine by using command `docker-v`
  * run this command in your terminal and it will display the version of docker.
  
![docker -v](https://user-images.githubusercontent.com/75534912/188781507-c76ce267-a040-42a1-beb5-c13acc4d7325.jpg)

* open the root dierectory of Anythink in terminal and use command `docker-compose up`
* If docker is runnign perfectly fine then, it wll start running containers and your backend and frontend get successfully link to each other.
