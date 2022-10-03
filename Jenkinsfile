pipeline {
    agent any
    tools {nodejs "NodeJS"}
    stages {   
//         stage ("Source") {
//             steps {
//                 sh 'git clone '
//                 sh 'npm install jest'
//             }
        }
        stage ("build") {
            steps {
                sh 'ant clean compile test package.war'
            }
        }

//         stage ("test") {
//             steps {
//                 sh 'npm test'
//             }
//         }

//          stage ("deploy") {
            
//          }
//     }
}
