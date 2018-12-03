pipeline {

environment {
BUILD_SCRIPTS_GIT="https://github.com/shivam75/JenkinsTest1.git"

BUILD_SCRIPTS='pipeline.groovy'

BUILD_HOME='/var/lib/jenkins/workspace'
}

agent any

stages {

stage('Build') {

steps {

echo "This is Step Build"
}

}

stage('Deploy') {

steps {

echo "This is Step Deploy"

}

}

stage('Test') {

steps {

echo "This is Step Test"

}

}

}

post {

always {

cleanWs()

}

}

}