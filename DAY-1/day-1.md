## google lcoud class-1 notes

* GCP organisation strcutre image

![org-strcutr](./images/gcp-oganisation-strcuture.svg)


* in the above, you can understood, __GCP__ start __organisation__
  * under the below __folder__
    * there is possibleity to create  __folder__ "inside the folder"
    * Under the __folder__ ,  we can createe __projects__
    * each __resource __ belongs to __project__

## GCP projet notes

* project name, project id, project number
* project name cane change at a nay tme
* project id --> we can chnage, we can give any name at the time of creating project
* project number will be givem by __google cloud__, it can chnage , upto life time of prioject
* each project is linked on billing account otherwsie __GCP__ does not aloow to create resources.
  * if __billing account__ is "not active" state, then __GCP does not allow to create resources__.

## GCP enable API concept


* to use any GCP service __frist we need to enable "API"__
  * to enable that  there ia GCp service __API & services__
  * to that service, seacrch for resspecive API
  * for  example the below image 
![api-serivices-1](./images/api-services-image-1.PNG)

  * click on the "eanble api service" 
    * for example __google  contianer registery__  , search for container registery

![api-serivices-2](./images/api-services-image-2.PNG)

    *  click  on "contianer registery"

![api-serivices-3](./images/api-services-image-3.PNG)

* in the same way __we can disable__ api, if we do not want ot use that service.



### compute engine

* it is  simliamr to AWS Ec2 servive
* to use compute service -- >first we need "enable" compute engine api

* whenever enable  __compute engineer api__, it will automatically create one "sercive account "at IAM-admin" GCP service.

![compute-1](./images/compute-1.PNG)

 ## create simple "ubuntu" instance & install apche webser , access fromw internrt

* click on "create instance"
![compute-2](./images/compute-2.PNG)

![compute-3](./images/compute-3.PNG)

![compute-4](./images/compute-4.PNG)

![compute-5](./images/compute-5.PNG)

![compute-6](./images/compute-6.PNG)

![compute-7](./images/compute-7.PNG)

![compute-8](./images/compute-8.PNG)

![compute-9](./images/compute-9.PNG)

* remaing things "leave" as default

![compute-10](./images/compute-10.PNG)

![compute-11](./images/compute-11.PNG)

* run the flollowing commandas to intall _-apache2 webserver in the VM

```
sudo apt update
sudo apt install apache2 -y
sudo systemctl enable apache2.service
```


* copy __public IP__ of the in the browser , it unable to dispaly  the webapage, because 80 port is not opened to internet.


* to open 80 port, we  need to create __firewall__ at __VPC__ service.

![compute-12](./images/compute-12.PNG)

* click on __firewall__

![compute-13](./images/compute-13.PNG)

![compute-14](./images/compute-14.PNG)

![compute-15](./images/compute-15.PNG)

![compute-16](./images/compute-16.PNG)

![compute-17](./images/compute-17.PNG)


* now 80 port is opned. web page is dispaled from internet.


