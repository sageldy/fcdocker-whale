def label = "mypod-${UUID.randomUUID().toString()}"
podTemplate(label: label, containers: [
    containerTemplate(name: 'maven', image: 'maven:3.3.9-jdk-8-alpine', ttyEnabled: true, command: 'cat'),
    containerTemplate(name: 'golang', image: 'golang:1.8.0', ttyEnabled: true, command: 'cat')
  ]) {
 
    node(label) {
        stage('Get a Maven project') {
            sh 'echo Get a Maven project'
        }
 
        stage('Get a Golang project') {
            sh 'echo Get a Golang project'
        }
 
    }
}
