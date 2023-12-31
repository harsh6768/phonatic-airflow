# phonatic-airflow

What is Airflow ?

1. Airlow is a platform to programatically author , schedule and monitor workflows.
2. **Workflows** :  A workflow is a sequence of tasks that processes a set of data .
3. Airflow is not :
                  1. Data Streaming
                  2. Data Processing


### Features Of Airflow : 

##### 1. Scalable :
 Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

##### 2. Dynamic : 
Airflow pipelines are defined in Python, allowing for dynamic pipeline generation. This allows for writing code that instantiates the pipeline dynamically.

##### 3. Extensible : 
 Easily define your own operators and extend libraries to fit the level of abstraction that suits your environment. 


### Components of Airflow : 

<img width="1438" alt="Airflow Component" src="https://github.com/harsh6768/phonatic-airflow/blob/master/airflow.png">
   

### Important Concept Of Airflow : 

##### DAG :
 Airflow DAGs are composed of Tasks.

##### Task : 
Each Task is created by instantiating an operator class . A configured instance of an Operator becomes a task.

##### DAG Run : 
When a DAG is started , the Airflow scheduler creates a DAG Run entry in its database.

##### Task Instance : 
When a task is executed in the context of a particular DAG Run , Task instance is created.



