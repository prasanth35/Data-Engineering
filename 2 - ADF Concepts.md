**Top Concepts:**
- Pipeline
- Activity
- Data Sets
- Linked Services
- Triggers

**1. Pipe Lines**
- Logical grouping of activities that performs a unit of work.
- A ADF can have one or more pipelines.
- This basically runs all your scripts/activities that you want to perform.

Steps to start with :
	- Create a new ADF from create resource.
	- Go to author and monitor.
	- Click of edit icon to access the pipelines.
	- Click on create new pipeline in the three dot icon.
	- Drag and drop components/activities to your pipeline.
	- Click on debug to run your pipeline testing.
	- Click on publish to publish your pipeline to the adf.
	- 

**2. Activity**

- Represents a processing step in a pipeline.
- Eg : Copy is an activity, run query is an activity.

**3. Linked Services**

- This contains all the services that can be linked with your adf.
- It contains all the connection strings of your services such as function apps, storage accounts, database credentials.
- You can connect to various services in the linked services directly with an connection string or you can fetch details from a azure vault for better security.

**4. Data Sets**

- Representation of data structure within a data store.
- This contains the connections of the input and the output data sources.

**5. Triggers**

- These are basically crons jobs to run your pipeline.
- There are three types
- Scheduled Trigger ( runs on calendar basis or time basis )
- Thumbling Trigger ( Runs on specific intervals and contains the state of the pipelines )
- Event Trigger ( Runs on specific event )
- Triggers are many to many relationship
- One trigger can run many pipeline or one pipeline can run many triggers. 
