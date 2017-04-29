# docker-python-app
Dockerize python application for a simple project or your practicing Python programming!  

# How to Use
```bash
docker build -t your-image-name .
docker run -it --rm --name your-container-name your-image-name
```

if you want to run your script, you can edit `Dockerfile` like below.

```diff
FROM python:3-onbuild
- CMD [ "python", "./script.py"]
+ CMD [ "python", , "./script.py"]
```
