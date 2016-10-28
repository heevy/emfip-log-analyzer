EMFIP Log Analyzer
-

This tool allows analysis of logs from EMFIP using ELK stack. 

How-to use this ?
--

 - start
 
   ```   
   docker-compose up -d
   ```
 - stop
 
   ```   
   docker-compose stop
    ```   
 - analyze logs
   - Copy zipped EMFIP logs into folder input-dir in following structure : {env}/{type}/{date}/{ip}/
   - For EMFIP type is usually data-gateway or web-portal. 
