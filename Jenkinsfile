pipeline {
agent any
stages {
stage('CheckoutModule1') {
        steps {
            sh 'mkdir -p Module1'
            dir("Module1")
            {
                git branch: "master",
                url: 'https://github.com/Himanshu-optit/sunbird-devops.git'
            }
        }
    }
stage('CheckoutModule2') {
        steps {
            sh 'mkdir -p Module1'
            dir("Module2")
            {
                git branch: "master",
                url: 'https://github.com/Himanshu-optit/sunbird-data-pipeline.git'
            }
        }
    }
}
}
