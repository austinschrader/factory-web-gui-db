# Dr. Sillystringz's Factory Database & Web GUI

## Description

The project allows Dr SillyStringz to manage his factory. His factory has both machines and engineers assigned to work on them. This web application allows him to manage those relationships, as well as store their data in MySQL.

By Austin Schrader, 1/8/2020

## .NET Core 2.2 Installation

- [Download .NET Core 2.2 for Windows here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.203-windows-x64-installer)
- [Download .NET Core 2.2 for MacOS here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer)

## MySQL & MySQL Workbench Installation

- [Download MySQL & MySQL Workbench for Windows here](https://dev.mysql.com/downloads/file/?id=484914)
- [Download MySQL & MySQL Workbench for MacOS here](https://dev.mysql.com/downloads/file/?id=484919)

## Project Setup

1. Clone or Download this repository
2. Navigate to the folder where you downloaded or cloned this repository
3. Now open your terminal and navigate to Factory.Solution > Factory
4. Type in `dotnet restore` to download necessary packages
5. Modify the file titled appsettings.json and input your MySQL password as the value for "pwd"
6. Import the MySQL database
7. Then type in `dotnet run` to run the application
8. Congratulations, this is the program!

## Import MySQL database

1. Open MySQL Workbench & enter in your MySQL password
2. Navigate to Administration
3. Click Data Import/Restore
4. Click the 'Import from Self-Contained File' radio button
5. Click the `...` button and navigate to the Downloaded/Cloned repository and double click on the SQL database
6. Select Dump Data & Structure
7. Start Import

## Clone this repository

1. Download this repository by clicking the "Code" button and then copy the url
2. Open a terminal and navigate to where you want the repository cloned to
3. Type in `git clone REPOSITORYURLHERE`
4. Congratulations, you cloned the repository.

## Download this repository

1. Download this repository by clicking the "Code" button and then "Download Zip"
2. Right click the downloaded file and "Unzip"
3. Double click on the file that was just unzipped
4. Congratulations, you downloaded the repository.

## Known Bugs

At this time, there are no known bugs. If you see spot a bug feel free to make a pull request.

## Technologies Used

- C#
- .NET Core 2.2
- MySQL & MySQL Workbench
- Object Oriented Programming
- MySQL
- MySQL Workbench
- Entity Framework
- Git
- Gitbash
- Github

## License

This repository is licensed under the MIT license.

Copyright (c) 2020 by _Austin Schrader_
