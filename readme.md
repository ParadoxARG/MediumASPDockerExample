# Contanerized ASP.NET Application Example

Simple example of a ASP.NET with a Windows Docker container application.

## Getting Started

Just copy the project and set it in motion!

### Prerequisites

* Visual Studio
	Installation guide: https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2017

* Docker
	Installation guide: https://docs.docker.com/install/#supported-platforms
		
## Deployment

For deployment you just need a device running docker.
Run the following commands in Powershell from the app root folder:
docker build -t containerName .
docker run -d containerName

## Built With

* Visual Studio
* Docker


## Versioning

It's a first and final version

## Authors

* **Tomas Guzman** - [ParadoxARG](https://github.com/ParadoxARG)


## License

This project is licensed under the GNU General Public License (GPL).

