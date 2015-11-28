# docker-bootstrap

Image with all the required components to compile and install bootstrap

This command will compile bootstrap to the dist directory:

```
docker run -it --rm -v $(pwd)/dist:/usr/src/bootstrap/dist fr3nd/bootstrap grunt dist
```
