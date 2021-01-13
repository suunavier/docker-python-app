[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://10-100-101-95.ip.mygitpod.com/#https://github.com/amazipangu/docker-python-app)

# docker-python-app
Dockerize python application for a simple project or your practicing Python programming!  

# How to Use

1. First, build your image.

  ```bash
  docker build -t your-image-name .
  ```

1. Then, run your container.

  ```bash
  docker run -it --rm --name your-container-name your-image-name
  ```

## Run your script!

if you want to run your script, you can edit `Dockerfile` like below.

```diff
FROM python:3-onbuild
- CMD [ "python"]
+ CMD [ "python", "./script.py"]
```
