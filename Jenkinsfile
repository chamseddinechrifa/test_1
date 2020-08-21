Node {
    agent {
        label 'master'
    }
    stages {
        stage ('clone') {
            steps {
                bat label: '', script: 'cd /d D:/Devops && git clone https://github.com/chamseddinechrifa/test_1'
            }
    

        }
        stage ('compiler') {
            steps {
                bat label: '', script: 'cd /d D:/Devops/test_1 && javac App.java '
            }
            
        }
        stage ('run') {
            steps {
                bat label: '', script: 'cd /d D:/Devops/test_1 && java App'
            }
            
        }
    }
}
