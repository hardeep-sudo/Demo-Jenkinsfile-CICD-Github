pipeline {
     agent any
     stages {
         stage('Checkout from SCM') {
            steps {
              checkout scm
            }
         }
         stage('Build') {
            steps {
              sh 'echo "Hello World"'
             }
         }
//         stage('Lint HTML') {
//              steps {
//                  sh 'tidy -q -e *.html'
//              }
//         }
     }
}
