# MVC

SECTION dotnet
Semicolons are terminating statements and are required
Variables - Explicit vs Implicit
Implicit
  var x = 
  OR 
Explicit
  int x = // string x = 

SECTION strings
String vs Char
  String is double quotes // ""
  Char is single quote for a single character // ''

Concat vs Interpolation
  string word = x + y // concat
  string word = $"{x} {y}" // $ creates ability to interpolate; @ allows for linebreaks

SECTION numbers
int represents whole numbers
double represents a decimal
float represents a decimal adding a f to the end; less precice then double
decimal represents a decimal adding an m to the end; more precice than double

SECTION boolean / math / conditional
bool x = // true OR false
equality: ==, >=, <=, !=
NO MORE TRUTHY OR FALSEY
conditionals must have some sort of comparision even if that is "!= null"

SECTION arrays (and how crappy they are)
string[] jCats = new string[7]{"Dudley", "Ironman", etc...};
Very not user friendly

List<string> jCats = new List<string>() {"Dudley"};
jCats.Add("Ironman");
jCats.Remove("Dudley");

SECTION objects
DO NOT USE OBJECT LITERALS (POCO's)
everything we use must have a data type!
  Models
    public, internal, protected, private
  Importing is now called "using"