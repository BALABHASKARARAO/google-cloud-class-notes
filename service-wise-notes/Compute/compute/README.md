## GCP compute 
* in this GCP service we can create virtual machines



## the below are Important notes of compute service

* premetiable VM's GCP is simialr to SPOT instances in AWS.
* purpose of Premetiabel VM's for running batch jobs, it does not impact on our work if VM is reastarted also.

*  VPC is global, subnet is regions specific

*  two VM's in the same __Availabilty zone in the sam "VPC" __ will communicatae each other.
* two VM in the same __regions in the sam "VPC"__ will communicatae each other.
* two VM in the same __different region in the sam "VPC"__ will communicatae each other.
* two VM in the same __different region in the "different" "VPC __ will not communicatae each other unles if we do the __VPC peering__.
