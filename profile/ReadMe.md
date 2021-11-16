# Roku
Roku is an Open-source web-based Project manager.  
The project was started by Nick van Oijen as a School Project.  
Roku is based on Trello, Jira and Github Projects.

# The Project
Roku currently contains 4 different projects:
| Project            | Language/Framework      | Repository |
|--------------------|-------------------------|------------|
| ApiGateway         | C# - .NET Core - Ocelot | [RokuAPIGateway](https://github.com/RokuOrg/RokuAPIGateway)|
| Project Service    | Golang                  | [RokuProjectService](https://github.com/RokuOrg/RokuProjectService)|
| Web App            | Javascript - React      | [RokuWebApp](https://github.com/RokuOrg/RokuWebApp)|
| Auth Service       | Typescript              | [RokuAuthService](https://github.com/RokuOrg/RokuAuthService)|

For any documentation about a specific project refer to the project's repository  
For research done on any topic refer to the [Research](https://github.com/RokuOrg/Research) repository  
# Documentation

## Architecture
The image below shows the high-level architecture design of Roku.  
![Image](/Images/RokuArchitecture.png)  
You can find the architecture of each individual service in it's repository.

## User Stories  

**US-1** - As user, I want my personal data to be saved, so I can close my project and not lose all my work.  
**US-2** - As user, I want to create projects, so I can implement my scrum methods.  
**US-3** - As user, I want to ass other users to my project, so they can see and make changes to my project.  
**US-4** - As user, I want to have a calendar where I can add my items, so I can plan my project.  
**US-5** - As user, I wany to label my items so i can organize them.  

## Database Model

The image below shows the database model of Roku.  
The green object is a part of the RokuAuth Service and the blue objects are a part of the project service.
![Image](/Images/DatabaseModel.png)