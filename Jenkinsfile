pipeline {
    agent any
    triggers {
         pollSCM('* * * * *') // Polling Source Control
     }

stages{
    stage('Build'){
        steps{
            echo 'Building'
        }
        
        }


    stage('Test'){
        steps {
            echo 'Testing'
        }
        
        }

    stage('Deploy'){
        steps {
            echo 'Deploying'
        }
        
        }
   
    }
}