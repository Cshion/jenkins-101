node {
    stage("Preparation"){
        checkout scm
    }

    stage("Build"){
        steps.sh "mvn test-compile"
    }

    stage("Unit Test"){
        steps.sh "mvn test"
    }
}
