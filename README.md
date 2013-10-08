Summary
-------

The following vagrant project will build a nice sandbox/training environment for the nodejs and angularjs tutorial (http://docs.angularjs.org/tutorial).

The main features are that it:
* Builds an Ubuntu x86_64 (12.04) virtualbox environment (vagrant-nodejs-angularjs) with nodejs and npm pre-installed  
* vagrant-nodejs-angularjs command line includes tree, vim, git, unzip packages plus some "useful aliases"
* All files can be accessed from the host side, enabling usage of more "user friendly" editors like sublime text
* I can also use my regular web-browser via port-forwarding ( http://localhost:4567/ ).
* finally as part of the install process it will clone git clone https://github.com/angular/angular-phonecat.git and branch to step-0 (git checkout -f step-0 )

I have setup a vagrant-nodejs-angularjs github repository (https://github.com/dgapitts/vagrant-nodejs-angularjs-tutorial.git)

So all you need to do (assuming you have vagrant and virtualbox already installed) is 

    git clone https://github.com/dgapitts/vagrant-nodejs-angularjs-tutorial.git
    cd vagrant-nodejs-angularjs
    vagrant up
  
It takes about 2 mins to build the new nodejs virtualbox server 

