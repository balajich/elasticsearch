# Starting elastic search
    sudo sysctl -w vm.max_map_count=262144
    docker-compose up
# Check health of nodes
     curl -X GET "localhost:9200/_cat/nodes?v&pretty"
# Stopping elastic search
    docker-compose down -v
