node('JDK11') {
    stage('vcs') {
        git branch: 'Test-Branch', url: 'https://github.com/MalineediRamarao/spring-petclinic.git'
    }
    stage("build") {
        sh 'mvn package'
    }
    stage("archive results") {
        junit '**/surefire-reports/*.xml'

    }
}
