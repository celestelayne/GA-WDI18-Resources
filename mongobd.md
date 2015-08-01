### [Mongo Shell Help](http://docs.mongodb.org/v2.2/tutorial/access-mongo-shell-help/#mongo-shell-help-collection)

##### ...[Getting Started with Mongo Shell](http://docs.mongodb.org/v2.2/tutorial/getting-started-with-the-mongo-shell/)

+ Open two terminal windows and cd into /usr/local
```
Celeste-Layne-2:local admin$ cd /usr/local
```
+ In the first window: run mongod
+ In the second window: type **./bin/mongo**
```
Celeste-Layne-2:local admin$ ./bin/mongo
```
+ Connect to database. In this case it's **test**
MongoDB shell version: 3.0.3
connecting to: **test**
Welcome to the MongoDB shell.
For interactive help, type "help".
For more comprehensive documentation, see
	http://docs.mongodb.org/
Questions? Try the support group
	http://groups.google.com/group/mongodb-user
+ In the repl, type **db** to display the database you are currently using:
```
> db
test
```
+ See, it's called **test** which is the default database
```
> show dbs
```
and it will return a list of all the databases:
```
art_app       0.078GB
artmapr       0.078GB
artmapr_app   0.078GB
artmapr_node  0.078GB
library_app   0.078GB
local         0.078GB
method_test   0.078GB
smashterHits  0.078GB
testing       0.078GB
todos_app     0.078GB
wine_app      0.078GB
```
+ To switch databases, issue the **use <db>** command:
> use artmapr
+ Now, we've switched to the artmapr database
+ To list the available databases, use the command **show dbs**. But I want to see th available collections, so to see the list of collections in the current database, use the **show collections** command:
```
> show collections
```
+ And here they are:
```
system.indexes
users
```
