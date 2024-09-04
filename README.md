# EventHub EventProcessor module on Azure Container Instances demonstration

## Introduction

Demonstration of running a stateful EventHub EventProcessor application within the Azure Container Instances.



## CLI commands and flow

If you want to play along, check the [az-cli-event-processor.md](az-cli-event-processor.md) file for building and deploying resources and the container instance.



## Environment variables

The following (sample) environment variables are used:

```
eventHubNamespaceUri = 'acs-eventprocessor-service-ehns.servicebus.windows.net' 
consumerGroupName = 'aci'
eventHubName = 'messages'
blobStorageUri='https://acseventhubchckpntstor.blob.core.windows.net/messagesacicheckpoints'
```



## Credits

This demonstration is based on:

* The [Event Hub processor](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-dotnet-standard-getstarted-send?tabs=passwordless%2Croles-azure-portal&WT.mc_id=AZ-MVP-5002324#update-the-code)
* The [first blog post introducing stateful processing using the ACI](https://sandervandevelde.wordpress.com/2024/08/24/getting-started-with-azure-container-instances/)
* The [blog post introducing the EventHub Event Processor running in the ACI](https://sandervandevelde.wordpress.com/2024/09/04/running-the-event-hub-event-processor-in-azure-container-instances/)


## MIT License

This application is made available under the MIT license. 
