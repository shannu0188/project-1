pipeline{

    agent any

    stages{
        stage('server hostname'){
            steps{
                sh 'hostname'
            }

        }
        stage('server uptime'){
            steps{
                sh 'uptime'
            }
        }
        stage('server disk usage'){
            steps{
                sh 'df -h'
            }
        }
        stage('server cpu details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('memory usage'){
            steps{
                sh 'free -h'
            }
        } 
        

    }
}
