pipeline {
agent any

 stages {
stage('Initial') {
steps {
echo 'Starting phase.......'
}
}
stage('Build-clean') {
steps {
bat 'mvn clean'
}
}
stage('Build-test') {
steps {
bat 'mvn test'
}
}
stage('Build-package') {
steps {
bat 'mvn package'
}
}
}
}