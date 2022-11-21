#!/bin/sh
pipeline{
        agent any
        stages{
            stage('Open Directory'){
                steps{
                    sh "cd ~/LBG7-Python-API"
		    sh "python3 lbg.py"
                }
            }
        }
}