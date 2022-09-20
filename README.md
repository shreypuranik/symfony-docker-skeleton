## Symfony Docker Skeleton

This project bundles the base Symfony framework with a MySQL container and Docker to aid with local development. 

### Cloning project 

Clone via git by running: 

```git clone https://github.com/shreypuranik/symfony-docker-skeleton.git```

### To run locally

* Clone this project locally 
* Navigate to your local project directory 
* Run the following command via cli 
* ```docker-compose up --build```
* This should spin up the required containers as specified in `docker-compose.yml`

### Setting up your application 

Once your Docker containers are ready, jump into the php container by running: 

```docker-compose exec php /bin/bash```

Once within the container, run the Symfomy command to set up your app in the same directory: 

```symfony new .```

From your browser, visit http://localhost:8082 and you should see your newly created Symfony app. 