# online resume for students

## Prerequisites

- [GitHub account]
- [Azure account]
- [Azure CLI]
- [.NET Core 3.1 LTS]
- [Azure Functions Core Tools]
- [Visual Studio Code]
- [Visual Code Extensions]
  - [Azure Functions Extensions]
  - [C# Extension]
  - [Azure Storage Extension]

## Front-end resources

The front-end is a static site with HTML, CSS, and JavaScript. It's static and has a visitor counter. The visitor counter data fetched via an API call to an Azure Function.

- [Azure storage explorer] is a handy tool to use when working with Storage Accounts
- This is how you can [deploy static site to blob storage.]
  
## Back-end resources

The back-end is an [HTTP triggered] Azure Functions with Cosmos DB input and output binding. The Function is triggered, it retrieves the CosmosDB item, add +1 to it, and saves it and returns its value to the caller.

- [Prerequisites for developing functions with visual code locally.]
- [Create a Cosmos DB account via command line] or [from the portal].
- [Create an HTTP triggered Azure Function in Visual Studio Code.]
- [Azure Functions Cosmos DB bindings]
- [Retrieve a Cosmos DB item with Functions binding.]
- [Write to a Cosmos DB item with Functions binding.]
- You'll have to [enable CORS with Azure Functions] for you website to be able to call it.

## Testing Resources

- [Testing is important.]
- [Getting Started with xUnit.net.]
- [How to setup Xunit with Azure Functions.]
- [Testing Azure Functions.]
  


