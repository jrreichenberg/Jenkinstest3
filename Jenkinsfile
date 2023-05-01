pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Building..."
            }
            post{
                success{
                    mail to: "jr1234567891011121314219328923@gmail.com",
                    subject: "Build status email",
                    body: "Build was successful"
                }
            }
        }
    }
}