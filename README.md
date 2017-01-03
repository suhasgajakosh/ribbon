# ribbon
How to execute: 

1. Run following command to build client and all server instances at /Ribbon
          mvn clean install
          
2. Run following command to execute client and all server instances, run from base folder of each project
          mvn spring-boot:run
          
3. To test if server instance is working, hit localhost:{port_number}/greeting API

4. To test Ribbon client is working, hit localhost:8888/hi API

5. Check which server instance was called at every hit of ribbon client API

