# Around: Geo-index base social network

* Developed an Android app for users to post events (geo-location, image, description, etc.)
* Deployed the web service, written in [Go](https://golang.org/), to [Google Cloud (GAE flex)](https://cloud.google.com/appengine/docs/flexible/) for better scaling
* Employed [ElasticSearch](https://www.elastic.co/) (GCE) to provide geo-location-based search functions such that users can search nearby posts within a distance 
* Utilized [BigQuery](https://cloud.google.com/bigquery/) to analyze posts dumped from [BigTable](https://cloud.google.com/bigtable/) by using [Google Dataflow](https://cloud.google.com/dataflow/)
* Improved the keyword-based spam detection by aggregating the data at the post level and user level  
