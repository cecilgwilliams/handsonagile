```
docker run --rm --detach \
--name=handsonagile \
--volume=$PWD:/srv/jekyll \
--publish 4000:4000 \
jekyll/jekyll:latest \
jekyll serve --baseurl /handsonagile
```
`http://127.0.0.1:4000/handsonagile/`

`docker logs -f handsonagile`
