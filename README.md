# drf-es-dsl-example

An example to test `bulk` insert of [Elasticsearch](https://www.elastic.co/) on [Django REST Framework](https://www.django-rest-framework.org/) with [elasticsearch-dsl](https://github.com/elastic/elasticsearch-dsl-py).

`docker compose up` and `docker compose down` to load up and shut down the servers.

Go to `http://localhost:9200/search_2/_search?pretty=true&q=*:*` upon completion of loading all the containers.
