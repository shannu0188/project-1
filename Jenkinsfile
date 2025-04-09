pipeline{

    agent any

    stages{
        stage(' server hostname'){
            step{
                sh 'hostname'
            }

        }
        stage('server uptime'){
            step {
                sh 'uptime'
            }
        }
        stage('server disk usage'){
            step{
                sh 'df -h'
            }
        }
        stage('server cpu details'){
            step {
                sh 'lscpu'
            }
        }
        stage( memory usage){
            step{
                sh 'free -h'
            }
        } 
        

    }
}
