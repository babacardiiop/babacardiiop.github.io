pipeline {
    agent any
    tools {
        jdk "jdk17-0-5"
    }
        stages{
        stage("Build"){
            steps {
                git 'https://github.com/babacardiiop/babacardiiop.github.io.git'
                dir("demo-retourdevacances"){
                sh "chmod +x ./gradlew"
                sh "./gradlew build"
                }
            }
        }
   }}
