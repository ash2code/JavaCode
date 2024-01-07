pipeline {
    agent any 
        tools {
            maven "M3"
        }
        stages {
            stage ("code-checkout") {
                steps {
                    git url "https://github.com/ash2code/JavaCode.git"
                }
            }
            stage ("code build") {
                steps {
                    sh "mvn clean package"
                }
            }
        }
}

                      
