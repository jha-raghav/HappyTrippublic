pipeline {
        agent UbuntuNode
        stages {
                stage('checkout'){
                        
                        steps {
                               echo 'starting checkout'
                               checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'ef1c4a29-cfdc-4b61-a8ca-93f13b747a8f', url: 'https://github.com/vmadykumar/HappyTrippublic.git']]])
                               echo 'checkout completed'
                        }
                }
        }
}
