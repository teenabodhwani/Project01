
pipeline {

  
    stages {
        stage('checkout') {
            steps {
                 script{
                        dir("terraform")
                        {
                            git "https://github.com/teenabodhwani/Project01.git"
                        }
                    }
                }
            }
    }
}
