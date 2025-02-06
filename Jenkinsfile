pipeline {
    agent any 

    stages {
        stage('GitCheckout') {  
            steps {
                script {
                    
                gitCheckout(
                    branch:"main",
                    url:"https://github.com/Gopalakrishna530/gopalDemo.git"
                )
                }
            }
        }
    }
}
