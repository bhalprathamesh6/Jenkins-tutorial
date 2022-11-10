pipeline {
    agent any
    stages {
        stage("PRATHAM 1") {
            steps {
                build job: 'PRATHAM_TEST1', parameters: [string(name: 'PRATHAM', value: "${params.MYPARAM}")]
            }
        }
        stage("PRATHAM 2") {
            steps {
                build job: 'PRATHAM_TEST2', parameters: [string(name: 'PRATHAM 2', value: "${params.MYPARAM}")]
            }
        }     
    }
}
