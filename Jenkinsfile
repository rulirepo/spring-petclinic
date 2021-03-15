node {
    stage('scm'){
        git 'https://github.com/rulirepo/spring-petclinic.git'
    }

    stage('build'){
        sh 'mvn package'
    }
}
    