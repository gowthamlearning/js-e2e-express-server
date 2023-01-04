pipeline{
    agent {label 'Nodejs'}
    stages{
        stage ('scm'){
            steps{
                git url:"https://github.com/gowthamlearning/js-e2e-express-server.git",
                branch:"main"
            }
         }
            
        stage ('build') {
            steps{
                npm install
                npm start
            }
            
        }
    }
}