# Around: Geo-index base social network

* Built a scalable web service in Go to handle posts and deployed to [Google Cloud (GAE flex)](https://cloud.google.com/appengine/docs/flexible/) for better scaling 
* Employed ElasticSearch (GCE) to provide geo-location-based search functions such that users can search nearby posts within a distance 
* Utilized [Google Dataflow](https://cloud.google.com/dataflow/) to implement a daily dump of posts to [BigQuery](https://cloud.google.com/bigquery/) table for offline analysis 
* Improved the keyword-based spam detection by aggregating the data at the post level and user level  
