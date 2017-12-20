node{
  checkout scm
  currentBuild.displayName = "UI-"+currentBuild.displayName
  concurrency : 2
  print 'something'
  print 'something else'
  sh 'git whatchanged -n 1'
  def me =sh (script:'git whatchanged -n 1 --pretty=format: --name-only',returnStdout:true).trim()
  print me
  
}
