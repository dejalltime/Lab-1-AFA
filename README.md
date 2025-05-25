
# Azure Functions with Output Bindings (Python)

This project demonstrates two Azure Functions using Output Bindings:
1. **Storage Queue Output Binding**
2. **Azure SQL Database Output Binding**

Both functions are written in Python and developed using Visual Studio Code.

---

## Setup Instructions

### Prerequisites
- Python 3.10
- Azure Portal
- Azure Subscription
- Azure Functions Core Tools v4
- Visual Studio Code with Azure Functions, Azure Storage, Azurite, and Python extensions
- Azure Storage Explorer

---

## Function 1: Storage Queue Output Binding

### Overview
This function is triggered via an HTTP request and sends a message to an Azure Storage Queue.

### Guides Followed
- [Create your first function](https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-vs-code-python)
- [Add output binding to Azure Storage Queue](https://learn.microsoft.com/en-us/azure/azure-functions/functions-add-output-binding-storage-queue-vs-code?pivots=programming-language-python&tabs=isolated-process)

## Function 2: Azure SQL Output Binding

### Overview
This function inserts a record into an Azure SQL Database upon HTTP trigger.

### Guides Followed
- [Create Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/database/single-database-create-quickstart?view=azuresql&tabs=azure-portal)
- [Add Azure SQL output binding](https://learn.microsoft.com/en-us/azure/azure-functions/functions-add-output-binding-azure-sql-vs-code?pivots=programming-language-python)

## Demo Video
Watch the full demo here: [YouTube Demo](https://youtube.com/your-demo-link)

---

## What I Learned
- How to connect and use Azure Storage Queues and SQL Database with Output Bindings.
- How to deploy Python Azure Functions to Azure.
- Practical use of serverless event-driven architecture.

---