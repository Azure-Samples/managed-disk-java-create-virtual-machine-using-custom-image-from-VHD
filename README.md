---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Compute
  platforms: java
---

# Getting Started with Compute - Create Virtual Machine Using Custom Image From VHD - in Java #


  Azure Compute sample for managing virtual machines -
   - Create an un-managed virtual machine from PIR image with data disks
   - Deallocate the virtual machine
   - Generalize the virtual machine
   - Create a virtual machine custom image from OS and Data disk VHDs of virtual machine
   - Create a second virtual machine using the custom image
   - Create a second virtual machine using the custom image and configure the data disks
   - Deletes the custom image
   - Get SAS Uri to the virtual machine's managed disks.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/managed-disk-java-create-virtual-machine-using-custom-image-from-VHD.git

    cd managed-disk-java-create-virtual-machine-using-custom-image-from-VHD

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.