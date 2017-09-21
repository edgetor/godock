# Go Dock
## Docker Compose for GO Projects

Includes:
------
  * Go (v. 1.9)
    * Glide for package management
  * Node
    * Runs YARN on path
  * Redis
  * Mongo

-----------

Create a .env file, a sample has been included
------

-----------
Your code will need a .env file, here is a sample:
------

```
HTTP_PORT=3000          # Should not be changed unless reflecting change in docker-compose.yml
REDIS_URL=redis:6379    # The url has to be to "redis"
MONGO_URL=mongo         # The url has to be set to "mongo"
MONGO_DB=my_mongo_db    # Can be any name you want
```
