pipeline{
    agent {
        labels 'node1'
    }
    stages {
        stage('git checkout'){
            steps{
                sh 'mkdir java_app && cd java_app && touch text{1..100}.txt'  
                git branch: 'main', url: 'https://github.com/praveen1994dec/Java_app_3.0.git'
            }
        }
    }
}
