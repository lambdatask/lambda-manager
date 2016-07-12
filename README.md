
curl -X POST --unix-socket /var/run/docker.sock http:/services/create -H 'Content-Type: application/json' --data-binary '@./service-create.json'

# Get service version inside GET return
curl -vv -X POST --unix-socket /var/run/docker.sock http:/services/<service_id>/update?version=<service_version> -H 'Content-Type: application/json' --data-binary '@./service-update.json'


# Take a look

* https://webtask.io/
* https://news.ycombinator.com/item?id=10477943
