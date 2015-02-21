# Mkdocs
[mkdocs](http://www.mkdocs.org/) is a simple static file genetor.
You can use it to generate a documentation site from YAML configuration file and
markdwon content

## Build it
```bash
git clone git@github.com:gianarb/docker-mkdocs.git
cd docker-mkdocs
docker build .
```

## Run it
```bash
docker pull gianarb/mkdocs
docker run -v /your/project/dir/:/opt/ gianarb/mkdocs
```
