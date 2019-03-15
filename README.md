# Demo1


This is an App for getting and monitoring weather conditions and geological data.
For our app we created two generators of random data to imitate IoT devices. 
This data will be modified in another two FAAS functions that contained in the Kubernetes cluster. 
After modification data send to “save-to-db” function and after that to Mongo DB.  
