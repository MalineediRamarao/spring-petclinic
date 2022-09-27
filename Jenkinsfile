pipeline {
    agent any
    stages {
        stage('testing') {
            steps {
                sh 'echo hello this is first declarative pipeline project'
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
