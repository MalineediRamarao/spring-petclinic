pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'echo hello'
            }
        }
        stage('learning') {
            steps {
                git url: 'https://github.com/MalineediRamarao/spring-petclinic.git', 
                    branch: 'Test-Branch-1'
            }
        }
    }
}
