pipeline {
    agent any // any agent... but what is 'agent'?

    stages {
        stage('Build') {
            steps {
                echo 'Building succeed ... hello from Freddie'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing succeed as well ... nihao from Freddie'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying done .... say bye to Freddie '
            }
        }
    }

    post{
        // Conditions:
        //  * always
        //  * success
        //  * failure
        always{
            // 
        }

        success{

        }
    }
}