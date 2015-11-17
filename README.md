# java-sfdc-bulk-api-app
## Create Properties
```
src → main → resources → conf → userInfo.properties
```

```
userId = <Your UserID>
password = <Your Password>
apiVersion = 34.0
authEndpoint = https://<login or test>.salesforce.com/services/Soap/u/
filePath = <Your File Path>/accounts.csv
```

##Run
```
$ cd SalesforceBulkDI
$ mvn spring-boot:run
```

##Package
```
$ mvn package
$ java -jar target/SalesforceBulkDI-1.0.0-SNAPSHOT.jar
```