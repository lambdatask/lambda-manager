
curl -X POST --unix-socket /var/run/docker.sock http://services/create -H 'Content-Type: application/json' --data-binary '@./service-create.json'
