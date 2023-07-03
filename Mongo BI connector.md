# For using the Tableau Cloud: 
- We can only connect to the Tableau Desktop with MongoDbusing the MongoDb Bi connector or the JDBC method. If we wish to make our Tableau Workbook, accessible remotely for our team to gain insights then we have to use the Tableau Cloud for the same, we have to publish the same over the Tableau Cloud, and if we are using the MongoDB as our Database then we have only one option to do the same that is using MongoDB connector to connect Mongo DB Atlas to the Tableau or we can Directly work upon the Tableau Online for the same, same credentials are needed for the same. We can just put in credentials according to the below-given instructions.




- We need is Hostname (Server name), port name, username, password and database name of our MongoDB Atlas base
- There is a requirement to fulfil the MongoDB Atlas connection with the Tableau
- MongoDB Atlas clusters above M10 or M10 supports the connection with the Tableau using the MongoDB BI connector
- Secondly, we must have enabled the Mongo BI tools support or the MongoDB BI connector tools in our MongoDB Atlas
- To connect to the BI Connector for Atlas:
   - Click the Connect button for your cluster.
   - Click Connect Your Business Intelligence Tool and connect with your BI tool with the provided connection information.
   - Setup Connection Securely > Choose a connection method > Connect
   - Choose the BI tool to which you have to connect the data to.
   - Copy the Hostname, User and Port details
   - Remember M10 or M20 clusters sometimes provide errors in the same.



# To connect to the BI Connector for Atlas:
- Click the Connect button for your cluster.
- Click Connect Your Business Intelligence Tool and connect with your BI tool with the provided connection information.
- Select Tableau as your BI tool
- Copy the Credentials.
- Could you make sure that you have enabled the BI Connector enabled for the Atlas?
  
