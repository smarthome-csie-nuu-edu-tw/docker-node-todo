Initializing a new instance
When the container is executed for the first time, it will execute the files with extensions .sh, and .js located at /docker-entrypoint-initdb.d.

In order to have your custom files inside the docker image you can mount them as a volume.