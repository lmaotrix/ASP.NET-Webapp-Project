
# User Management With C#
This is a User Management WebApp made with ASP.NET Core to learn C#'s features and to learn **Database connection with SQL** and **CRUD operations** (CREATE, READ, UPDATE, and DELETE).


## Features

- Add Users to the system and save into a database
- Remove Users from the system and save changes
- Edit Users' information and save the changes


## Usage

1. clone the repository using Git CLI

```bash
  git clone https://github.com/lmaotrix/ASP.NET-Webapp-Project.git
  cd .\Mystore\
```
2. install SQLClient, SQLite or MySQL through one of the following links:
- SQLClient: https://www.microsoft.com/it-it/sql-server/sql-server-downloads
- SQLite: https://www.sqlite.org/index.html 
- MySQL: https://www.mysql.com/downloads/


Open Visual Studio or your IDE of choice and open the repository you cloned

I personally Used SQLClient.


Open a database connection on Visual Studio by going on:

**view** --> **server explorer** --> **Connect to Database** --> put the **required information** (check below for how to find the instance name) --> press '**ok**' and then press '**yes**' on the popup

### How to find the instance name for the database connection

1. open CMD and type:
```bash
  services.msc
```
2. look for the SQL server [look for 'SQL Server (SQLEXPRESS)']

3. on CMD, type the following command:
```bash
  sqlcmd -S localhost\SQLEXPRESS
```

4. after pressing 'enter', type the following commands:
```SQL
  select @@version
  go
```
5. to close the connection, type
```SQL
  exit
```


    
## Feedback

If you have any feedback, please reach out to me at coco.gian07@gmail.com

