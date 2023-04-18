build job: 'exm', parameters: [string(name: 'msg', value: 'main')]

node{
    stage('build stage')
    {
        echo "hi ${params.msg}"
        git url: 'https://github.com/Navyanavi31/maven.git', branch:"${params.msg}"
    }
}
