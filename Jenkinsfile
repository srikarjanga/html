// node('test') {

//     //Stage -01
//     stage('checkout-code') {
//    // This stage is to bring code from github
//    git 'https://github.com/srikarjanga/html.git'
        
//     }
//     //Stage one ended
    
//     //stage -02 started here
//     stage('executing_shell_commend') {
    
//     sh label: '', script: 'sudo cp /home/ubuntu/Srikar/workspace/html-pipelines/* /var/www/html/'
// }
//     //stage -02 ended here     
// }

pipeline {
    agent any 

    stages {
        stage ('SCM Checkout') {

            steps {
                git 'https://github.com/srikarjanga/html.git'
                echo "This is bring our source code from github"
            }

        stage ('command') {
            steps {
                sh label: '', script: 'sudo cp /home/ubuntu/Srikar/workspace/html-pipelines/* /var/www/html/'
            }
        }
        }
    }
}