# MVC


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
