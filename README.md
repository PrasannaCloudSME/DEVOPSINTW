# DEVOPSINTW


1. What is the difference between mesh topology and hub and spoke topology ?

# Topology Structure:

Mesh Topology: In a mesh topology, every device in the network is connected to every other device. This creates a fully interconnected network where each node has a direct link to every other node.
Hub-and-Spoke Topology: In a hub-and-spoke topology, devices are connected to a central hub (or a central node). The hub acts as a central point of communication, and all communication between devices passes through the hub.
Redundancy:

Mesh Topology: Mesh networks provide high redundancy and reliability because there are multiple paths for data to travel. If one link or node fails, alternative paths can be used to maintain connectivity.
Hub-and-Spoke Topology: Hub-and-spoke networks may have a single point of failure at the central hub. If the hub fails, all communication between devices may be disrupted.
Scalability:

Mesh Topology: Scaling a mesh network can become complex as the number of nodes increases because each node needs to be directly connected to every other node.
Hub-and-Spoke Topology: Hub-and-spoke networks are generally easier to scale. New devices can be added by connecting them to the central hub without the need for direct connections between all devices.
Cost:

Mesh Topology: Implementing a mesh topology can be more expensive due to the numerous connections required. However, the cost may be justified by the increased reliability.
Hub-and-Spoke Topology: Hub-and-spoke networks are often more cost-effective to set up, especially for smaller networks. The central hub can be a single point of control and management.
Flexibility:

Mesh Topology: Mesh networks offer greater flexibility and adaptability. They can easily accommodate changes, additions, and reconfigurations without affecting the entire network.
Hub-and-Spoke Topology: Hub-and-spoke networks may require more effort to reconfigure or adapt as changes often involve the central hub.

2. How to access azure vm from onprem

3. How to patch azure vms

4. Azure backup

5. Azure monitor

6. Sensitive contents in terraform

7. gitignore file in github   A .gitignore file is used in Git to specify files and directories that should be ignored and not tracked by version control. This file is particularly useful when you want to exclude certain files or directories from being included in your Git repository, especially files generated during the development process or containing sensitive information.

Here's a simple guide on how to use a .gitignore file in GitHub:

Create a .gitignore File:

Create a file named .gitignore in the root directory of your Git repository.
Specify Files and Directories to Ignore:

Open the .gitignore file using a text editor.
Add lines specifying files, directories, or patterns that you want Git to ignore. 

8. Recovery services vault

In Azure customer portal how will you login to tenant

difference between declarative and imperative language

Difference between System Assigned Identity & User Assigned Identity

Log Analytics/KQL

Azure Policies

Entra ID

Network Topology

1.How do you store passwords in terraform?

2.Difference between ARM templates and Terraform.

3.Explain State File in terraform., Where we store a state file

4.explain the structure in terraform.

5.Explain the structure of the ARM template.

6.how you protect the azure VM?

7.Difference between variable and parameter.Variable:

A variable is like a storage box that holds a value or information in a computer program. It is a named container used to store and retrieve data during the execution of the program.
Parameter:

A parameter is like a placeholder for a value that a function or method expects to receive. It's a way of passing information into a function. When the function is called, the parameter takes on the value provided during the call.

8.Difference between parameter and variable in a terraform.

9.How you ensure security in AAD?

10.What default policy azure applied in subscriptions.

11.what are the Azure VNET topologies.
Azure Virtual Network (VNet) allows you to create private, isolated networks in the Azure cloud. There are several VNet topologies and configurations based on your specific requirements. Here are some common Azure VNet topologies:

Hub-and-Spoke Topology:

In a hub-and-spoke topology, there is a central hub that connects to multiple spoke VNets. The hub serves as a central point for connectivity, and spokes connect to the hub. This topology is often used for scenarios where you want to centralize network management and control traffic flow between different VNets.
Mesh Topology:

In a mesh topology, every VNet is connected to every other VNet. This provides a fully interconnected network, and all VNets have direct connections to each other. While this offers high redundancy, it can become complex to manage as the number of VNets increases.
Multi-Region Topology:

You can create VNets in different Azure regions and establish connectivity between them using Azure Virtual Network Peering or VPN gateways. This topology is useful for scenarios where you need to extend your network across geographically dispersed locations.
Isolated Virtual Networks:

Each VNet operates in isolation, with no direct connectivity to other VNets. This is a simple and straightforward topology suitable for scenarios where you want to keep different environments or applications separate.
Transitive Routing:

Azure Virtual Network Peering allows for transitive routing between peered VNets. This means if VNet A is peered with VNet B and VNet B is peered with VNet C, then traffic can flow from VNet A to VNet C through the peering relationship. This provides flexibility in designing more complex network architectures.
Virtual WAN (Wide Area Network):

Azure Virtual WAN is a networking service that simplifies complex connectivity scenarios by providing optimized and automated branch-to-branch connectivity through Azure's backbone infrastructure. It's suitable for connecting multiple branch offices, VNets, and applications.
On-Premises Connectivity:

VNets can be connected to on-premises networks using Azure VPN Gateway (Site-to-Site or ExpressRoute). This allows you to extend your on-premises network into Azure.
Hybrid Cloud Topology:

In a hybrid cloud topology, you connect on-premises networks, branch offices, and Azure VNets to create a seamless and integrated network. This often involves using Azure ExpressRoute for dedicated private connectivity.
12.how you peer hub and spoke networks.

13.terraform dependencies?

14.first resource you created in terraform, second resource you are trying to create using the output of first terraform. do you specify depends on? or terraform automatically knows?

15.How do you make your VM use a firewall?

16.how do you enforce Policy in azure?

17.how you give access to a user for 20 minutes to a particular resource in a subscription?

18.which scenarios do you recommend a client for Mesh topology and Hub-spoke topology?

19.you changed the infrastructure using GUI manually, how terraform knows the change?

20.why modules in terraform needed?

21.how you store passwords in Github?

22.which service do you use to backup vm?

23.what are the azure services you used?

24.explain the azure application gateway?

25.why we need Infrastructure as a Code?

26.what is the use of "deploy if not exist" in azure?

27.why we need to apply policy in azure.

28.what is the use of DSC(Desired state configuration)?

29.what are the resources you have provisioned in terraform?
