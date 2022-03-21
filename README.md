
# Run these two commands and compare the result

```
docker run --rm -it -v $(pwd):$(pwd) -w $(pwd) quay.io/goswagger/swagger:v0.25.0 flatten index.yml
docker run --rm -it -v $(pwd):$(pwd) -w $(pwd) quay.io/goswagger/swagger:v0.26.0 flatten index.yml
```
