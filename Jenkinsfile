node {
    stages {
        stage ('clone') {
            steps {
                bat label: '', script: 'git clone https://github.com/chamseddinechrifa/test_1'
            }
    

        }
        stage ('compiler') {
            steps {
                bat label: '', script: ' javac App.java '
            }
            
        }
        stage ('run') {
            steps {
                bat label: '', script: ' java App'
            }
            
        }
    }
}
