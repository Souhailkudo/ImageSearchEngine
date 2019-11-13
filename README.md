# ImageSearchEngine

This is a simple project that uses elasticsearch to make a search engine on a photo database. The search is based on text tags that are stoed with image information.
These information can be used to make the URLs of the pictures to display the search results. The metadata used is provided in the link below.
First thing to do is to install elasticsearch then inject the data to an elasticsearch server. The mapping .json file is used to create the index in elasticsearch. If you want to inject the data in elasticsearch using Logstash, you can use the .conf file provided.
After setting up elasticsearch it's time to run the flask server that would start the search engine knowing that FLASK_APP=app.py.
