pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                snDevOpsConfigRegisterPipeline()
                snDevOpsStep()
                out.info(this,"SOME VERY USEFUL INFORMATION")
                echo 'Hello World'
            }
        }
        stage('testeeeeee') {
            steps {
                snDevOpsConfigRegisterPipeline()
                snDevOpsStep()
                snDevOpsChange()
                out.info(this,"SOME VERY USEFUL 2INFORMATION")
                echo 'Hello World'
            }
        }
    }
}
