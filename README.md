# How to generate Resume after changes

assumes docker is running
```
docker run --rm -v $(pwd):/home/yamlresume yamlresume/yamlresume build my-resume.yml
```