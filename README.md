## Clean Architecture
Read about Clean Arhitecture [here](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html). Essentially, it is a multi-layered approach to design an application, where each layer is
Framework Independent, Testable, Independent of UI/Database/External Services.

This is a .Net Core 3.1 MVC based Web Application, with in-built Bootstrap 4, Microsoft Identity, Entity Framework Core.

## Demo App:
This project is deployed on [https://cleanarchdotnetcore.azurewebsites.net](https://cleanarchdotnetcore.azurewebsites.net)

## Build status
![Build](https://github.com/naveenalavilli/CleanArchitecture/workflows/Build/badge.svg)

  

## Tech/framework used
* .Net Core 3.1
* MS SQL
* Bootstrap 4
* JQuery

## Features
* User Authentication, using Identity, and OAuth providers (Google,Facebook,LinkedIn)
* SendGrid support, to send emails.
* CRUD for States. This can be used as example to work on other Entities in any project.
* PWA Support. The users can install this app on their Mobiles , without getting from PlayStore/AppStore.
* SeriLog Support , to log events/Exceptions in the database.
* Uses JQuery, BootStrap 4 and Font Awesome

## Installation
* Clone the project from GitHub
* Configure Database in AppSettings.Json
* Run update-database in Pakage Manager Console , with Default Project set to Persistence
* Configure OAuth settings in AppSettings.json, if desired.

## Credits
* Microsoft Docs
* Tons of blogs, tutorials on Youtube.
* Stack Overflow!

## Questions
* you can write to me at [https://www.linkedin.com/in/alavilli](https://www.linkedin.com/in/alavilli/)
