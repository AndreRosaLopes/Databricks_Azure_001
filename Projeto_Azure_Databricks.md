# Azure + Databricks

# Settings the services: 

> Create a resource > Storage > Storage accounts ![alt text](Projeto_Azure_Databricks/image.png)

![alt text](Projeto_Azure_Databricks/image-1.png)

> Review + Create

![alt text](Projeto_Azure_Databricks/image-2.png)

> Go to resource

Create the medallion arquicteture

![alt text](Projeto_Azure_Databricks/image-3.png)

Data storgae > Containers > + Container

![alt text](Projeto_Azure_Databricks/image-4.png) > ![alt text](Projeto_Azure_Databricks/image-5.png)

Create bronze, silver and gold container:

![alt text](Projeto_Azure_Databricks/image-6.png)


# Activating  Databricks

Microsoft Azure > Inside "resource group" > Create > Search: Azure Databricks > Create

![alt text](Projeto_Azure_Databricks/image-7.png) > ![alt text](Projeto_Azure_Databricks/image-8.png) > ![alt text](Projeto_Azure_Databricks/image-9.png)

![alt text](Projeto_Azure_Databricks/image-10.png)

![alt text](Projeto_Azure_Databricks/image-11.png)

Review + create > create > Go to resource > Launch Workspace

Finally, we have Databricks!!! 

# Working with Notebook - Databricks

Workspace > Workspace > Users > Create > Notebook

## Upload the file...

Return to Microsoft Azure home > storage account > Container > bronze > Upload

Upload the file SRAG_01-06.csv


## Mount the path to file

Storage account > Security + networking > Access Key > Show > Copy

![alt text](Projeto_Azure_Databricks/image-13.png)

## Follow the notebook...

## checking the files created:

![alt text](Projeto_Azure_Databricks/image-14.png)

And inside _delta_log folder:

![alt text](Projeto_Azure_Databricks/image-15.png)

## checking gold:

![alt text](Projeto_Azure_Databricks/image-16.png)

![alt text](Projeto_Azure_Databricks/image-17.png)




