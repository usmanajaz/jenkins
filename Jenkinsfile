pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "========executing Build========"
            }
            post{
                success{
                    mail to: "usmanajazkhan@gmail.com",
                    subject: "Jenkins Build report",
                    body: "the build was successfull yipee"
                }
            }
        }
        stage("Test"){
            steps{
                echo "========Testing========"
            }
        }
        stage("Deploy"){
            steps{
                echo "========Deployingd========"
            }
        }

    }
}