#!/usr/bin/env groovy
pipeline{
    agent any
    stages{   
        stage("testing maven"){
            steps{
                
                sh 'mvn test'
                
            }
        }
        stage("maven package"){
            steps{
                
                sh 'mvn package'
                
            }
        }
    }
}