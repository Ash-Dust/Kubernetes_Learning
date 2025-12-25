What is Container, Docker and K8s?
What is Container? How does it different from traditional VM?

VMs will have a OS and an App all run on a Virtualization.
Containers, instead of Virtualization, use Container Runtime and also have an App on it.
--> So Container have no OS.

Now you may ask, What is the different between Virtualization and Container Runtime?
Answer: Virtualization wil have it's own OS for the vitualization while Container Runtime is created to control a existed Linux feature.
To put it simply, Virtualization: a host will devide into independences OS VMs, Container Runtime will have all application run on a host.

*Note:   It's is not recommended to run Windows apps- in Container.

Here another problem arise, So what distinguish a traditional on-prem host vs a container host?
So here, What container do is it will separate two processes while on a traditional on-prem host, the processes can see/conflicts each other.
A simple example here is, container will have 2 separate apps like mySQL, and this will cause no conflicts because they are different from each other. While on-prem host, processes might have conflict over each other, for example, 2 mySQL is having the same port (80/443 etc) which will cause errors.

*Note: Container must have atleast 1 process or else it will off or deteled.
#Remember the process inside a VM or Container
