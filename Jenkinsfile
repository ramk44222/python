pipeline{
    agent any
    environment {
        ENV = "hi"
    }
        stages{
            stage('first build'){
                steps {
                    sh "echo $ENV"
                }
            }
        }

}
