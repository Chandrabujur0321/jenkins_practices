pipeline{
    agent any
    stages{
        stage('enviroment steup') {
           steps{
            script{
                def doc = readyaml file : "congig/deployment/xyz.yaml"
                print doc
            }
           }
           
        }
    }
}