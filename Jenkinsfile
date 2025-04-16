pipeline{
  agent {
    label 'Java_slave_node'
  }
  tools{
    maven 'maven'
  }
  stages{
    stage(" preparing build "){
      steps{
        sh 'mvn clean package'
    }
  }
}
}
