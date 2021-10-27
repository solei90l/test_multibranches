pipeline {
    agent any 
<<<<<<< HEAD
    
    tools {
       gradle 'Gradle-6.2'
    }
    stages {
        stage('run frontend') {
            steps {
                echo 'executing yarn' 
                nodejs('Node-10.17'){
                  sh 'yarn install '         
                }
            }
        }
      stage('run backend') {
            steps {
                echo 'executing gradle'
                sh './gradlew -v'
               
=======
    stages {
        stage('build') {
            steps {
                echo 'Building the app' 
            }
        }
      stage('test') {
            steps {
                echo 'Testing the app' 
            }
        }
      stage('deploy') {
            steps {
                echo 'Deploying the app' 
>>>>>>> origin/features
            }
        }
    }
}
