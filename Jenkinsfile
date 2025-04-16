pipeline{
  agent {
    label 'Java_slave_node'
  }
  stages{
    stage("print server info"){
      steps{
        sh """ echo ${env.BUILD_ID}
        echo ${env.JOB_NAME}
        pwd
        whoami
        uptime
        echo \$HOSTNAME
        """
      }
    }
  }
}
