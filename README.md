##### Clone this project from https://github.com/nanuchi/my-project for practicing github actions
    Turorial https://www.youtube.com/watch?v=R8_veQiYBjI&t=643s 
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
