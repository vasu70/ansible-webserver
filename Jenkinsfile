pipeline {
    agent{ label "agentfarms" }
    stages{
        stage('Delete the workspace'){
            steps{
                cleanWs()
            }
        }

    stage('Second stage'){
            steps{
                echo "Second Stage"
            }
        }

    stage('Third stage'){
            steps{
                 echo "Third Stage"
            }
        }    
    }
}
