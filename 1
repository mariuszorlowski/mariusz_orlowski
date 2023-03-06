pipeline {
    agent {
      label 'slave01'
    }
    options {
        buildDiscarder logRotator(artifactDaysToKeepStr: '7', numToKeepStr: '3')
        timestamps()
        timeout(5)
        
    }
    
    environment {
        envs = "stage,pff,prod"
        deploy = "true"
    }
    
    stages {
        
        stage("Check environment") {
            steps {
                echo "env.envs"
                echo "env.deploy"
            }
        }
        
        stage("Check timeout") {
            options {
                timeout(time: 30, unit: 'SECONDS')
            }
        
            steps {
                sh "sleep 60"
            }
            
        }
        
    }

    post {
      always {
        cleanWs()
      }
    }
}
