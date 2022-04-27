pipeline{
    agent any
    environment {
        ENV = "hello"
    }
        stages{
            stage('first build'){
                steps {
                    sh "echo $ENV"
                }
            }
        }

}
