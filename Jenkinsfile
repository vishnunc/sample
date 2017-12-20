node{
  checkout scm
  currentBuild.displayName = "UI-"+currentBuild.displayName
  concurrency : 2
  print 'something'
  print 'something else'
  sh 'git whatchanged -n 1'
  sh 'git whatchanged -n 1 --pretty=format: --name-only'
  sh 'git diff-tree --name-only HEAD^ HEAD'
}
