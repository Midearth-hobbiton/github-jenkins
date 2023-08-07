pipeline {
    agent any 
    stages {
        stage('build') {
            environment {
                SHORT_SECRET = credentials("SHORT_SECRET")
                LONG_SECRET = credentials("LONG_SECRET")
                DOUBLE_SECRET = credentials("DOUBLE_SECRET")
                SUPER_LONG_SECRET = credentials("SUPER_LONG_SECRET")
                SECRET_TEXT = credentials("SECRET_TEXT")
            }
            steps {
                ls -al /var/lib/jenkins/workspace
                echo "Hello world"
                echo 'Run the static analysis to the code' 
                echo "Hello123456789world"
                echo "Hello world123456789"
                echo "Hello world, 123456789"
                echo "123456789Hello world123456789"
                echo "1234|56789, 12345678,9"
                echo "1223456789"
                echo "987654321"
                echo "[\123456789] \$123456789 %123456789 *123456789 @123456789"
                echo "long secret 1628b3ffb655acf6a3f87d9aecb2e78f6b2a051b426ee4774a1f52c43a788d978bcaa7ab2880d454dc376f1b57b3fa434af7"
                echo "super long secret a97929230e224e61506ef1199683056c51b7271ffa57e3dcff98fc7dbee15ad4bd914ff05d6c2b62990ce74da89ff70c28d53e6527f30ab22e4da83c45253a4541c92066b0074573b718fd2351a4554010f5c0c344e15a8b60a99885d8c42dba393310f8"
            }
        }
        // stage('Compile') {
        //     steps {
        //         echo 'Compile the source code' 
        //     }
        // }
        // stage('Security Check') {
        //     steps {
        //         echo 'Run the security check against the application' 
        //     }
        // }
        // stage('Run Unit Tests') {
        //     steps {
        //         echo 'Run unit tests from the source code' 
        //     }
        // }
        // stage('Run Integration Tests') {
        //     steps {
        //         echo 'Run only crucial integration tests from the source code' 
        //     }
        // }
        // stage('Publish Artifacts') {
        //     steps {
        //         echo 'Save the assemblies generated from the compilation' 
        //     }
        // }
    }
}
