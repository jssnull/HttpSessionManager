
## Http Session Manager
A http API session management.
Practical use case: A ecommerce site


# To-do:
- [ ] Add session expiration feature
- [ ] Update basket feature
- [ ] Test workflow
- [ ] Add skinny ORM support in service layer
- [ ] Production and Development environments built in Docker/Docker compose

# In process:
- [ ] Add Tests
# Done:
- [x] Add logout feature
- [x] Add login feature
- [x] Private endpoints available only for authenticated users
- [x] Retrieve basket feature

#### Project main components:
* Play Framework
* SBT

### Endpoints:
POST /login 

#### User info endpoint:

GET  /index/"user_name" 

#### Get user current basket:

GET  /basket/"user_name"


#### Home page endpoint:
GET  /home


## Running

```
sbt run
```

And then go to http://localhost:9000 to see the running web application.

