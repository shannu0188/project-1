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
        stage('calender'){
            steps{
                sh 'cal'
            }
        } 
        stage('date and time'){
            steps{
                sh 'date'
            }
        }
        stage('insatll httpd'){
            steps{
                sh ' sudo yum install https -y'
            }
        }

    }
}
