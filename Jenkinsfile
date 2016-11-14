node ('puppet-master'){

   stage('Updating example puppet-modules') {
      
      checkout scm
      
      sh 'echo jenkins | sudo cp -rf example /etc/puppet/modules/ && echo jenkins | sudo chown -R root:root /etc/puppet/modules/example'
      
      step([$class: 'WsCleanup'])
        
   }
   
}
