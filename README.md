# Common Docker Services
Tired of reading the docs and installing a service by entering line by line commands on terminal? 😪

This is a solution for that...🎉

You can use this repo as a collection of all the common service, which I use quite frequently, in many of my projects.

## Easy Peasy Steps
1. Clone the repo
2. Go to any service directory you want to use
3. You can go over the docker-compose file and see the volume mapping, some services like DB services has these to let the DB service import from a **.sql** file at the beginning
4. Run the following command, to run the service, while inside a service repository
```sh
docker-compose up --build
```
### That is IT!

# Want to contribute?
Feel free to fork the repository and raise a PR for other common service that you use!
