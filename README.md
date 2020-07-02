# Spring_cloud_config---properties_files
1. Deploy Config server.
2. create 4 instances of eureka server to test eureka cluster.
    check if host name is set in "C:\Windows\System32\drivers\etc\hosts"
    set Spring.profiles.active for each instance
    test localhost:all the 4 hosts.
3. create 2 instance of CallDetailMS for deployment using profiling. (CallDetailMS.YML is used instead of properties file for profiling).
    set spring.profiles.active
4. start other microservices.
