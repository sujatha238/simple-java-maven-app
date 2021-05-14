pipeline {
    agent any 

    //agent {
    //    docker {
    //        image 'maven:3.8.1-adoptopenjdk-11' 
    //        args '-v /root/.m2:/root/.m2' 
    //    }
    //}
    stages {
        stage('Build') { 
            steps {
                sh 'echo Hello Word to Sample Java App'
                sh 'cat README.md'
                //sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
