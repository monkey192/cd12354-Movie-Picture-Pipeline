##

### Cmd
- docker build
```
docker build -t frontend:latest . 

docker build -t frontend:latest --build-arg REACT_APP_MOVIE_API_URL=http://localhost:5001 . 
```
- run
```
docker run -it -p 80:3000 frontend:latest
```