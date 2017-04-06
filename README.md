# arcgispg
Docker is a great technology that allows you to host your application in small jails of memory called containers. 

We use this technology to quickly spin up a postgres instance that has all the neccessary requirements to create enterprise geodatabase. 


How to use this repo:

To pull ArcGIS 10.5 compatible docker container of postgres (9.5). This command will pull and run a container.

docker run --rm -p 5432:5432 husseinnasser/arcgispg:105


To pull ArcGIS 10.4.1 compatible docker container of postgres (9.4) This command will pull and run a container.

docker run --rm -p 5432:5432 husseinnasser/arcgispg:1041

Enjoy
Hussein
Follow me on twitter @hnasr

