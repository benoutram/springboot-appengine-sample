# springboot-appengine-sample

### Create the database ###
gcloud beta sql databases create gcloud_sample --instance=INSTANCE_NAME

### Describe the instance to get the connection string ###
gcloud beta sql instances describe INSTANCE_NAME
