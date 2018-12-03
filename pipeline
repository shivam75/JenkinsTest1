pipeline {

environment {
}

agent test

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
