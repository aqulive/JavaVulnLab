properties([disableConcurrentBuilds()])

pipeline {
    agent{
        label 'master'
    }
    options{
        buildDiscarder(logRotator(numToKeepStr: '10', artifactNumToKeepStr: '10'))
        timestamps()
    }
    stages{
        stage("SAST"){
            steps{
                sh 'pwd'
            }
        }
    }
}