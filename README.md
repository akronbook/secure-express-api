# How to install mongoDB on Mac
Install HomeBrew on your local machine by running this command :
/usr/bin/ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Once this is executed, you can check if it is installed correctly by typing
$brew --version

Install MongoDB with brew
$ brew install mongodb

Check if it is installed correctly
$ mongod --version

Create a folder in var/mongodb in /data/db using below command
sudo mkdir -p /data/db
sudo lakeeast /data/db

# How to run MongoDB
mongod

# How to run MongoDB Shell
mongo

Now you can perform mongo operations on your MongoDB server
show dbs

# How to create a new database
use <your-database-name>

# Example of creating a database and insert records
mongo
use passport-jwt  <!---This will create the database, but show dbs will not show the content as it is empty-->
var car = {model:  "Honda City", company: "Honda", year: 2017};
db.vats.save(car) <!-- Results will be shown -->



