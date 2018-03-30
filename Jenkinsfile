pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                maven 'mvncfg' {
                    sh 'mvn compile'
                }
            }
        }

        stage ('Package Stage') {

            steps {
                maven 'mvncfg' {
                    sh 'mvn package'
                }
            }
        }


        
    }
}
