# SET UP LOCALHOST TO SONARQUBE

    - Reference: https://hub.docker.com/_/sonarqube

    - Run on command line:
        
        sudo sysctl -w vm.max_map_count=262144
        
        sudo sysctl -w fs.file-max=65536

        ulimit -n 65536

        ulimit -u 4096

# Up Service

    - Run on command line:
 
        docker-compose up -d

# Access SonarQube

    - Reference: https://docs.sonarqube.org/latest/setup/get-started-2-minutes/

        Once your instance is up and running, Log in to http://localhost:9000 using System Administrator credentials:

        login: admin

        password: admin