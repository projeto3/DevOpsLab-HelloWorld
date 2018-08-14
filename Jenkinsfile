node {
    stage 'Git workspace'
    git 'https://github.com/projeto3/DevOpsLab-HelloWorld/jenkinsfile.git'

    stage 'Build venv'
    sh 'virtualenv --python=python3.6 venv'

    stage 'Install deps'
    sh './venv/bin/pip/ install -r requirements.txt'

    stage 'Unit tests'
    sh './venv/bin/py.test -ra -v --flaskes ./test.py'

    stage 'Deploy'
    echo 'Será feito deploy em um determinado provedor de aplicação!'
}

