node{
    stage('scm'){
        git branch: 'main', url: 'https://github.com/awstrainingsept/spring-petclinic.git'
    }

    stage('build'){
        sh "mvn clean package"
    }

    stage('postbuild'){

    }

}
