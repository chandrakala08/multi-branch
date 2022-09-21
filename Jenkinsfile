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
<<<<<<< HEAD
     }
    }
}
=======
        }
    }
>>>>>>> 3f7d049e97112c58759ebdc542e46010a6f0ae8f
