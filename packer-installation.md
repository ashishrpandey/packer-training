
Download the binary and unzip it -
  
      wget https://releases.hashicorp.com/packer/1.6.0/packer_1.6.0_linux_amd64.zip

      unzip packer_1.6.0_linux_amd64.zip

      mv packer /usr/bin/
  
  
There could be another binary named packer. so create an alias

    alias packer='/usr/bin/packer'
 
Verify that it is working

    [root@ip-172-31-46-86 ~]# packer
    Usage: packer [--version] [--help] <command> [<args>]

    Available commands are:
        build       build image(s) from template
        console     creates a console for testing variable interpolation
        fix         fixes templates from old versions of packer
        inspect     see components of a template
        validate    check that a template is valid
        version     Prints the Packer version

Check the current pakcer version 

      packer version 



