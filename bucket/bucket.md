### Create a bucket
```sh
gcloud storage buckets create gs://my-practice-bucket0606 \
    --default-storage-class=STANDARD \
    --location=US \
    --uniform-bucket-level-access \
    --public-access-prevention


gcloud storage buckets create gs://my-practice-bucket0606-shell
```