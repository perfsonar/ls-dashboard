# ls-dashboard
This is the exported version of the Public Lookup Service Dashboard, available at stats.perfsonar.net.

In order to use it, you have to import it into Grafana Instance:

 1. Go to Home > Dashboards > New > Import
 2. Upload the JSON file

## Prerequisites

 Please configure the Data Source:

 1. Go to Home > Administration > Data Sources
 2. Search and enable Elasticsearch Data Source

 Put the following configuration parameters:

 * Name: Elasticsearch
 * HTTP > URL: http://35.223.142.206/lookup
 * Elasticsearch details > Index name: lookup
 * Elasticsearch details > Time field name: expires

Save and Test.
