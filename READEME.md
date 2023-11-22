## Load API description

```bash
wget https://github.com/lenra-io/api/releases/latest/download/load-api.sh -O - -q | bash
```

## Generate

```bash
docker run --rm -v $PWD:/local --workdir /local openapitools/openapi-generator-cli batch gen-conf/php.yml
```
