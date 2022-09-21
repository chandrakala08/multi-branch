pipeline{
    agent any
    stages{
        stage("git cheak out"){
            when {
                branch "develop"
            }
            steps{
                echo"git cheak out completed"
            }
        }
        stage("maven build"){
            when {
                branch "develop"
            }
            steps{
                echo "maven build completed"
            }
        }
        stage("qa testing"){
            when {
                branch "qa"
            }
            steps{
                echo "testing qa"
            }
        }
        }
    }
