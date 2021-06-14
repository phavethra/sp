pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'sp') {
                    sh 'mvn clean compile'
                }
            }
        }

     
    }
}
