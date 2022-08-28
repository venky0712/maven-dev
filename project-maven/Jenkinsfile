node{
    stage("git") {
       git branch: 'main', credentialsId: '6e070d7b-950d-4c64-9818-2419b11f3210', url: 'https://github.com/venky0712/maven-dev/tree/main/project-maven'
     }
     stage("build") {
        def mvnhome = tool name: 'maven', type: 'maven'
        sh "${mvnhome}/mvn clean install"
     }
}
       
