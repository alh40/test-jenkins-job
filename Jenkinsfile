pipeline{
        agent any
        stages{
            stage('Open Directory'){
                steps{
                    sh "cd ~/LBG7-Python-API "
                }
            }
            stage('Run App'){
                steps{
                    sh "./lbg.py"
                }
            }
        }
}