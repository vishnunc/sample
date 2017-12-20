node{
  checkout scm
  concurrency : 2
  print 'something'
  print 'something else'
  def me =sh (script:'git whatchanged -n 1 --pretty=format: --name-only',returnStdout:true).trim().split('/')
  def package= me.length>1?me[1]:'.'
  currentBuild.displayName = package+currentBuild.displayName
}
