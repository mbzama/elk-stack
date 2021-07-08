# elk-stack

### To start the elk stack
	./start-elk.sh
	
### To stop the elk stack
	./stop-elk.sh

### Verify the docker containers
	docker ps
	(or)
	docker-compose ps

### Verify the elastic search
	curl -X GET "localhost:9200/_cat/nodes?v&pretty"

### Login to Kibana
	http://localhost:5601/
	