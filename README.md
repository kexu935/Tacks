# Tacks: a Geo-index based Social Network
This repository only contains backend. Frontend with web screenshots is here: [https://github.com/kexu935/tacks-web](https://github.com/kexu935/tacks-web)
* Built a social network website for users to post events (geolocation, image, description) using [ReactJs](https://reactjs.org/)
* Designed an interactive user interfaces using ReactJS libraries (antd, react-google-map, react-grid-gallery, react-router, etc.)
* Developed backend web service in [Go](https://golang.org/) and deployed to [Google Cloud (GAE flex)](https://cloud.google.com/appengine/docs/flexible/) for better scaling
* Employed [ElasticSearch](https://www.elastic.co/) (deployed on GCE) to provide geolocation-based search functions such that users can search nearby posts within a distance 
* Utilized [BigQuery](https://cloud.google.com/bigquery/) to analyze posts dumped from [BigTable](https://cloud.google.com/bigtable/) by using [Cloud Dataflow](https://cloud.google.com/dataflow/) to understand system work load, user distribution, etc.
* Improved the keyword-based spam detection by aggregating the data at the post level and user level
* Implemented authentication using OAuth 2.0 and utilized Redis to improve cache performance
