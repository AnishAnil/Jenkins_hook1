
//Jenkinsfile (Declarative Pipeline)

pipeline {
   agent any
   environment {
       first_path = env.JOB_NAME
   }
   stages {
       stage('example') {
            //agent { label 'master' }
            steps {
               echo 'SCM Checkout..'
               git 'https://github.com/AnishAnil/Jenkins_hook1.git'
                print(env.first_path)
            }
        }
    }
}
 
// pipeline {
//     agent any

//     stages {
//         stage('Build') {
//             steps {
//                 echo 'Building..'
//             }
//         }
//         stage('Test') {
//             steps {
//                 echo 'Testing..'
//             }
//         }
//         stage('Deploy') {
//             steps {
//                 echo 'Deploying....'
//             }
//         }
//     }
// }
