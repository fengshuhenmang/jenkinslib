@Library('jenkinslib')
def tools = new org.devops.tools()
pipeline{
    agent any
    stages{
        stage("This is 1"){
            steps{
                echo "Hello world"
            }
        }
        stage("This is 2"){
            steps{
                script{
                    tools.PrintMes("this is my lib!"，"green")
                }
                
            }
        
        }
    }
}
