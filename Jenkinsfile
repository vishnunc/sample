node{
  checkout scm
  currentBuild.displayName = "UI-"+currentBuild.displayName
  concurrency : 2
  print 'something'
  print 'something else'
  sh 'git log'
}
