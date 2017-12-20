node{
  checkout scm
  currentBuild.displayName = "UI-"+currentBuild.displayName
  concurrency : 2
  print 'something'
  print 'something else'
  sh 'git whatchanged -n 1'
  sh 'git diff-tree'
}
