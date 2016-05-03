# mule-runtime-manager
Mulesoft runtime manager command line client

Usage 
  
    $ ./runtime_manager --help
    usage: runtime_manager [-h] [--username USERNAME] [--password PASSWORD]
                           [--env ENV] [--op OP]
                           [--deploy-artifactname DEPLOY_ARTIFACTNAME]
                           [--deploy-file DEPLOY_FILE]
                           [--deploy-target DEPLOY_TARGET] [--debug]
    
    Deploy a mule application (zip) to an environment
    
    optional arguments:
      -h, --help            show this help message and exit
      --username USERNAME   Anypoint Username
      --password PASSWORD   Anypoint Password
      --env ENV             Environment (default Production)
      --op OP               Operation to run
                            [servers|groups|clusters|applications|targets|deploy]
      --deploy-artifactname DEPLOY_ARTIFACTNAME
                            Artifact name to deploy when using "--op deploy"
      --deploy-file DEPLOY_FILE
                            Filename to deploy when using "--op deploy"
      --deploy-target DEPLOY_TARGET
                            TargetName (find targets using --op targets, e.g.
                            "servers/mule01" or "groups/mule") when
                            using "--op deploy"
      --debug
