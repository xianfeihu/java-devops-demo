pipeline{
    agent any
    environment {
        hello = "123123"
        name = "xxxxxx"
    }

    stages {
        stage('代码编译') {
            steps {
                echo "编译。。。"
                echo "$hello"
                echo "${name}"
                pwd
                sh 'pwd && ls -alh'
                sh 'printenv'
            }
        }
        stage('代码测试') {
            steps {
                echo "测试。。。"
            }
        }
        stage('代码打包') {
            steps {
                echo "打包。。。"
            }
        }
        stage('代码部署') {
            steps {
                echo "部署。。。"
            }
        }
    }
}