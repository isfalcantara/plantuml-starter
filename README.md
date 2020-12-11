# PlantUML Docker Compose and VSCode starter files

Simple way to setup a PlantUML development environment by using Docker Compose and Visual Studio Code.

For the best experience, use [Visual Studio Code](https://code.visualstudio.com/) with the [PlantUML extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml).

## Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [PlantUML VSCode extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

## Installation

1. Clone the repo: `git clone git@github.com:isfalcantara/plantuml-docker-compose.git`
2. Rename it to whatever you like: `mv plantuml-docker-compose my-awesome-diagrams`
3. Change to the directory: `cd my-awesome-diagrams`
4. Run the Docker container: `docker-compose up -d`
5. Open Visual Studio Code: `code . && exit`

## Useful information

From there you can follow the instructions in the [PlantUML extension page](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) on how to install and use the extension.

The project already has a `.vscode` folder that contains some specific configuration for the PlantUML extension, such as:

- The PlantUML server is set to `localhost:8080` to use the Docker container instead of the web service.
- All generated diagram files are placed in the `out` folder.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- [My Linkedin profile](https://linkedin.com/in/isfalcantara)
- [Twitter @isfalcantara](https://twitter.com/isfalcantara)
