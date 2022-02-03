pipeline    {
            agent any
            stages {
             stage('BUILD'){
                steps {
                        git branch: 'main', url :'https://github.com/reddyprashanth305/java-codes.git'
                        sh 'mvn clean install'
                    }
                  }
