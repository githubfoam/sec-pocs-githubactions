# sec-pocs-githubactions
[![jwt-null-signature-vulnerable-app CI workflow](https://github.com/githubfoam/sec-pocs-githubactions/actions/workflows/ubuntu-workflow.yml/badge.svg)](https://github.com/githubfoam/sec-pocs-githubactions/actions/workflows/ubuntu-workflow.yml)  

~~~~
        vagrant up vg-nagios-01 
        git clone https://github.com/DataDog/security-labs-pocs.git     
        cd security-labs-pocs/proof-of-concept-exploits/jwt-null-signature-vulnerable-app/
        ls -lai
        docker build . -t vulnerable-app
        docker image ls
        # docker run -p 8080:8080 --name vulnerable-app --rm vulnerable-app
        # docker container ls
~~~~