pipeline{
  agent any
  stages{
    stage('abc')
    {
      steps{
        sh "kubectl get pods --kubeconfig /admin.conf"
      }
    }
  }
}
