This repository is the code sample for the Tech Artifacts Blog - https://techartifacts.com/build-and-deploy-net-core-applications-using-docker-containers/

"Build and Deploy .NET Core applications using Docker Containers"

To clone and run the code from this repository, you will need to follow these steps:

Open a terminal or command prompt and navigate to the directory where you want to clone this repository.

Use the git clone command to clone the repository from GitHub. The repository URL can be found on the GitHub page for the repository. 

For example:
```
git clone <git_repository_url>
```

Navigate to the directory of the cloned repository:
```
cd NetCoreWithDockerDemo
```

Restore the required NuGet packages by running the following command:
```
dotnet restore
```

Build the solution by running the following command:
```
dotnet build
```

Run the application by running the following command:
```
dotnet run
```

This will start the application and you should be able to access it in your web browser at http://localhost:5011 (or a different port if specified in the application's configuration).