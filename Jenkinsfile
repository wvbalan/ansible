stage "Deploy to production"

node {
    wrap([$class: 'AnsiColorBuildWrapper', colorMapName: "xterm"]) {
        ansiblePlaybook(
            playbook: 'gns3.yml',
            inventory: 'inventory.ini',
            credentialsId: ' 8b1ac09606f89267ec0854152748c45de46952be',
            colorized: true
            )
    }
}
