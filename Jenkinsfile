pipeline    {
            agent any
            stages {
             stage('BUILD'){
                steps {
                        git 'https://github.com/sharath030/javaproject.git'
                            sh 'mvn clean install'
                    }
                  }
            }
}
