pipeline {
 agent any
 stages {
 stage('Build') {
 steps {
 sh 'g++ -o PES2UG20CS394-1 ./main/hello.cpp'
 echo 'Building is successful'
 }
 }
 stage('Test') {
 steps {
 sh './PES2UG20CS394-2'
 echo 'Testing is successful'
 }
 }
 stage('Deploy') {
 steps {
 echo 'Deploying is successful'
 }
 }
 }
 post {
 failure {
 echo 'Pipeline has failed'
 }
 }
}
