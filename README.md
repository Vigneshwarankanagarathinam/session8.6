Session8
Assignment 6
To check the status of a job submitted in hortonworks cluster :
          
          You can use the Application State API to query the application state. To return only the state of a running application, use the following command format:
                                 
                    curl 'http://localhost:8088/ws/v1/cluster/apps/application_1409421698529_0012/state'
 
           You can also use the value of the Location field (returned in the application submission response) to check the application status. For example:

                    curl -v 'http://localhost:8088/ws/v1/cluster/apps/application_1409421698529_0012'
