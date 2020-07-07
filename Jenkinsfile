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

node ('test') {
    stage ('checkout') {
        git 'https://github.com/srikarjanga/html.git'
    }

    stage ('command') {
        sh label: '', script: 'sudo cp /home/ubuntu/Srikar/workspace/html-pipelines/* /var/www/html/'
    }

    stage ('srikar') {
        echo "This is srikar stage"
    } 

    stage ('satish') {
        echo "This is satish stage"
    }

    stage ('deepa') {
        echo "This is deepa stage"
    }
}