# HelpWanted

A website for posting about and requesting help for projects you are working on or have finished

Currently (and for the rest of version 1), the website assumes a MongoDB database is set up on localhost, otherwise the website will crash

Alternatively, the project can be run in a docker image with docker-compose or a mongodb access URI can be passed in through enviroment variables

In order for the website to work, you must set a client id, client secret, and oidc authority in Properties/launchSettings.json (or any other method of passing in enviroment variables)
