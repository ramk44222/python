pipeline{
    agent any
    environment {
        ENV = "ram"
    }
        stages{
            stage('first build'){
                steps {
                    sh "echo $ENV"
                }
            }
        }

}
