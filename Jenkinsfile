// pipeline {
// //   agent any
//   agent { node {label 'workstation' } }
//
//   environment {
//   TEST_URL = "google.com"
//   SSH = credentials("centos-ssh")
//   }
//    options {
//        ansiColor('xterm')
//    }
//    parameters { }
//
//    triggers { pollSCM('*/1 * * * *') }
//
//   stages {
//     stage('compile') {
//       steps {
//         echo 'Hello'
//         echo 'TEST_URL'
//         echo 'SSH'
//         sh 'env'
//         sh 'ansible -i 172.31.22.91, all -e ansible_user=${SSH_USR} -e ansible_password=${SSH_PSW} -m ping'
//       }
//     }
//   }
//   post {
//     always {
//       echo 'post'
//       //send email
//       //Trigger Another Job
//       // Update JIRA status about the build.
//     }
//   }
// }



pipeline {
  agent any

  stages {
    stage('Compile') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Test') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Code Quality') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Code Security') {
      steps {
        echo 'Hello World'
      }
    }
    stage('App Deploy') {
      steps {
        echo 'Hello World'
      }
    }
  }
}