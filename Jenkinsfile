node ('ansible'){
    stage(scm){
        git'https://github.com/Rajulolabhattu/ansible.git'
    }
    stage(build){
        sh label: 'ansible', script: 'ansible-playbook -i hosts util.yml'
    }
}