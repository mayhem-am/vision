Web Application for deploying neural net model on [Render](https://render.com)

The repository can be used as a starting point to deploy any model on Render.

Changes can be tested locally by installing Docker and using the following command:

```
docker build -t aiSight . && docker run --rm -it -p 5000:5000 aiSight
```

The guide for production deployment :







Officially time to shift from Heroku to Render :

* Although being expedient, moving from AWS to Render eliminated a lot of infrastructure complexity.
* GCP recommended for students but compares nothing against AWS Services.

Choose wisely
