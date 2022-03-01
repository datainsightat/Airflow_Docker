# Airflow

This containerfile is based on the Udemy Course [The Complete Hands-On Introduction to Apache Airflow](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow/)

## Build Container

    $ docker build -t airflow .

## Run Container

    $ docker container run --rm -d -p 8080:8080 airflow