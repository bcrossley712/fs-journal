# MVC
SECTION SETUP in appsettings.Development.json and appsettings.json
  "CONNECTION_STRING": "server=SG-brian-sql-6001-mysql-master.servers.mongodirector.com;port=3306;database=BrianDB;user id=Brian;password=Password123!",
  "AUTH0_DOMAIN": "dev-bcrossley712.us.auth0.com",
  "AUTH0_AUDIENCE": "https://brian-dev.com"

After setup:

SECTION table definition
  CREATE TABLE of your collections

SECTION Repositories
  Dumb... Only take what you give it and talk with the Database 

SECTION Crud methods for Repository
POST  
  INSERT INTO ^collection
  ()
  VALUES
  ()
GET
  SELECT * FROM ^collection
GET BY
  SELECT * FROM ^collection WHERE id = ^var
PUT
  UPDATE ^collection
  SET
    ^name...
  WHERE id = ^var
DELETE
  DELETE FROM ^collection WHERE id = ^var LIMIT 1

SECTION Interfaces
  Kind of like a blueprint
  Rule we set for the application

SECTION Inheritance
  Essentially have two or more different models for one class
  
