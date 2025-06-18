# How to generate Resume after changes

* assume docker is running*
```
docker run --rm -v $(pwd):/home/yamlresume yamlresume/yamlresume build my-resume.yml
```