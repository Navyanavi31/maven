properties([parameters([choice(choices: 'main\npr', name: 'msg')])])

node{
    stage('build stage')
    {
        echo "hi ${params.msg}"
        git url: 'https://github.com/Navyanavi31/maven.git', branch:"${params.msg}"
    }
}
