node ('puppet-master'){

   stage('Updating example puppet-modules') {
      
      checkout scm
      
      sh 'yes | cp -rf example /etc/puppet/modules/ && chown -R root:root /etc/puppet/modules/example'
        
   }
   
}
