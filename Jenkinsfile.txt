pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                dir('C:/Users/user/Desktop/Jenkins/test.bat') {
                    /* execute commands in the scripts directory */
                }
            bat 'C:/Users/user/Desktop/Jenkins/test.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/user/Desktop/Jenkins/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/user/Desktop/Jenkins/test.bat'
            }
        }
      stage('Package') {
            steps {
                dir('C:/Users/user/Desktop/Jenkins/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/user/Desktop/Jenkins/test.bat'
            }
        }
        stage('Deploy') {
            steps {
                dir('C:/Users/user/Desktop/Jenkins/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/user/Desktop/Jenkins/test.bat'
            }
        }
    }
}
