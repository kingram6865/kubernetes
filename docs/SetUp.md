#INTRO

Using Kubernetes requires either a bare metal server, or a VM (Virtual Machine)
which would, in turn reside on a bare metal server.

For AWS and GCP, Kubernetes use is baked in a bit, so preparing the system 
from scratch is not a skill that these cloud services require.

I have not worked with Azure, (nor do I wannt to, honestly) so I don't know
if that Microsoft product uses Kubernetes.

This documentation is a diary of steps taken to use Kubernetes in a private
ONPREM (On Premises) solution. 

#Premlinary

Configure a machine for use as a K8s Master node.
- Minimum 2 CPUs, 2G Ram

Other machine instances will be worker nodes.
- Minimum 1 CPU, 1 G Ram (or whatever the proposed application will need)
