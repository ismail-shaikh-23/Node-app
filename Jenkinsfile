pipeline{
    agent any 
    
    stages{
        
        stage("clone"){
            steps{
                git url: "https://github.com/ismail-shaikh-23/Node-app.git" , branch: "main"
            }
            
        }
        
        stage("build"){
            steps{
                echo "build stage"
                sh "docker-compose up -d"
            }
        }
        
        stage("done"){
            steps{
            echo "successfull"
            }
                
            }
    }
    
}

