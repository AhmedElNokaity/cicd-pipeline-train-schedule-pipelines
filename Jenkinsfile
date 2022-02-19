pipeline {
  agent any
  }
  stages {
    stage('Build') {
      steps {
          sh './gradlew build'
      }
    }
  }
  }
//   post 
//   {
//     always {
//       script {
//         if (env.BRANCH_NAME != 'master') {
//           sh '''
//             docker-compose down
//           '''
//         }
//       }
//     }
//   }
//}