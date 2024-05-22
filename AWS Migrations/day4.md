### Database Setup

* Goal 
   * Lets setup Microsoft SQL Server 
   * Import some sample Database
   * Migrate to AWS RDS 

### Microsoft SQL server setup  

* supported SQL Server Versions Refer here: https://docs.aws.amazon.com/dms/latest/userguide/CHAP_Source.SQLServer.html
* Lets create windows EC2 instance in AWS which will stimulate on-premises Microsoft SQL Server.
* for mac user have to download windows remote desktop viewer
![preview](images/16.png)
![preview](images/17.png)
![preview](images/18.png)
* use Windows+r = mstsc -v 
![preview](images/19.png)
![preview](images/20.png)
![preview](images/21.png)
![preview](images/22.png)
![preview](images/23.png)
* Generate password from the pem file. connect to windows vm using `mstsc -v <public ip/dns>`
* Install microsoft sql server 2017 and SQL Server Management studio as discussed in the class (refer video recording)
* For sample data lets use Adventure works Refer :https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
* 
![preview](images)![preview](images)![preview](images)![preview](images)