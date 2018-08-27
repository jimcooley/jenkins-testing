stage(start){
  node {
    echo 'Hello World'
    sh 'echo "Hello World" > hello.txt'
    sh "echo '${JOB_BASE_NAME}' > hello.txt"
    archiveArtifacts 'hello.txt'
  }
}
