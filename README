## BUILD ##
```
docker build -t tolkien .
```

## RUN after build ##
```
docker run -it --rm -d -p 8080:80 --name tolkien tolkien
```

## RUN with new code, without new build ##
```
docker run -it -p 8080:80 -v <path to>/code:/usr/share/nginx/html tolkien
```