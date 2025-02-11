## Running from DOCKERHUB

1. To clone the app navigate to your projects folder and run:

```
git clone <repo link>
```
2. Then use the following command to build the image locally:
```
cd todoapp && docker build . -t todoapp:1.0.0
```
3. To run created container use next command:
```
docker run -p 8080:8080 --name todoapp todoapp:1.0.0
```
4. Connect to the server using your browser http://127.0.0.1:8080/ 

    You can change the port by altering -p tag like -p 80:8080 will map port 80 to your app 

## Running from DOCKERHUB

 Execute the following command to pull and run the container:
```
docker run workpolly/todoapp:1.0.0
```
