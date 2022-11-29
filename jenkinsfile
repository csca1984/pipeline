pipeline {
    agent any // 
    //agent {
    //    kubernetes {
    //        cloud 'kubernetesiac'
    //        label JenkinsUtils.buildKubernetesLabel('iac-ansible')
    //        yamlFile 'JenkinsAgentPod.yml'
    //    }
    stages {
        stage('Build') {
            
            steps {
                //sh 'gradle --version'
                echo 'build de la aplicacion'
            }
        }

        stage('test') {
            
            steps {
                //sh 'gradle --version'
                echo 'test de la aplicacion'
            }
        }

        stage('deploy') {
            
            steps {
                echo 'deply de la aplicacion'
            }
        }
    }
}
