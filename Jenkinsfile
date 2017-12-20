node{
  checkout scm
  currentBuild.displayName = "UI-"+currentBuild.displayName
  concurrency : 2
  print 'something'
  print 'something else'
  def me =sh (script:'git whatchanged -n 1 --pretty=format: --name-only',returnStdout:true).trim().split('/')
  print me.length>1?me[1]:me[0]
  
}
