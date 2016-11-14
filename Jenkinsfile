node ('puppet-master'){
   
   timestamps {

      stage('Updating example puppet-modules') {
      
         checkout scm
      
         sh 'echo jenkins | sudo -S cp -rf example /etc/puppet/modules/ && echo jenkins | sudo -S chown -R root:root /etc/puppet/modules/example'
      
         step([$class: 'WsCleanup'])
        
      }
   
   }

}
