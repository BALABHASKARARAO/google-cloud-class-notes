## gcloud commmands for compute

*  Prerequisities 
```
gcloud config set project <project id>
```
* gcloud config set compute/zone us-central1-c
* gcloud components list

* gcloud compute project-info describe --project <your_project_ID>

* gcloud compute instances create --help
* gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone $ZONE
* gcloud compute instances describe gcelab2
* gcloud compute ssh gcelab2 --zone us-central1-c