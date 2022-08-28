node{
    stage("git") {
      git 'https://github.com/venky0712/maven-dev'
     }
     stage("build") {
        def mvnhome = tool name: 'maven', type: 'maven'
        sh "${mvnhome}/mvn clean install"
     }
}
       
