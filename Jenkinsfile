//@Library('roboshop') _
//
//component="user"
//
//nodejs()

pipeline {


    agent {
        node {
            label 'workstation'
        }
    }

    options {
        ansiColor('xterm')
    }


    stages {

//            stage('Code Quality') {
//                steps {
//                    sh 'sonar-scanner -Dsonar.projectKey=${component} -Dsonar.host.url=http://172.31.82.179:9000 -Dsonar.login=admin -Dsonar.password=admin123 '
//                    sh 'echo Code Quality'
//                }
//            }
//            stage('Unit Test Cases') {
//                steps {
//                    sh 'echo Unit Test Cases'
//                }
//            }
//            stage('Chechmarx SAST scan') {
//                steps {
//                    sh 'echo Chechmarx SAST scan'
//                }
//            }
//            stage('Chechmarx SCA scan') {
//                steps {
//                    sh 'echo  Chechmarx SCA scan'
//                }
//            }

        stage('one'){
            steps{
                sh 'echo hello world '
            }
        }
    }
    post{
        always {
            cleanWs()
        }
    }


}