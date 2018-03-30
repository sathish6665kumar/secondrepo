pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'mvncfg') {
                    sh 'mvn compile'
                }
            }
        }

        stage ('Package Stage') {

            steps {
                withMaven(maven : 'mvncfg') {
                    sh 'mvn package'
                }
            }
        }


        
    }
}
