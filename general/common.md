### List regions
```sh
gcloud compute regions list
```

### Create an environment variable
```sh
INFRACLASS_REGION=us-east1
echo $INFRACLASS_REGION
```


### Append the environment variable to a file
```sh
mkdir infraclass
touch infraclass/config
echo INFRACLASS_REGION=$INFRACLASS_REGION >> ~/infraclass/config

INFRACLASS_PROJECT_ID=project-9bf11e95-a2f3-4ef8-ad5
echo INFRACLASS_PROJECT_ID=$INFRACLASS_PROJECT_ID >> ~/infraclass/config

# Use the source command to set the environment variables
source infraclass/config
echo $INFRACLASS_PROJECT_ID
```