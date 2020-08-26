pipeline { 
    agent any 
    stages {
   
        stage('Test'){
            steps {
                withMaven(maven : 'apache-maven-3.6.3'){
                        bat "mvn package"
                }

            }
    }
}
}
