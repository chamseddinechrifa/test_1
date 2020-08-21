node {
        stage ('clone') {
                bat label: '', script: 'git clone https://github.com/chamseddinechrifa/test_1'
        }
        stage ('compiler') {
                bat label: '', script: 'cd test_1 && javac App.java '
        }
        stage ('run') {
                bat label: '', script: 'cd test_1 && java App'   
        }
    
}
