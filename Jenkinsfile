pipeline {
    agent any
    tools {ant "ANT"}
    stages {   
        stage ("Source") {
            steps {
                sh 'git clone https://github.com/aasimrazajatoi/SampleWebApp.git'
//                 sh 'npm install jest'
            }
        
        stage ("build") {
            steps {
                sh 'ant info'
            }
        }

//         stage ("test") {
//             steps {
//                 sh 'npm test'
//             }
//         }

//          stage ("deploy") {
            
//          }
   }
}
