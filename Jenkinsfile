pipeline {
agent any
stages {
stage(‘Build’) {
steps {
sh "C:\Program Files\apache-maven-3.9.0-bin\apache-maven-3.9.0\bin\mvn clean package"
}
}
stage(‘Test’) {
steps {
sh "C:\Program Files\apache-maven-3.9.0-bin\apache-maven-3.9.0\bin\mvn test"
}
}
}
}
