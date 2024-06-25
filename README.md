# QUICKKART-THE-E-COMMERCE-APPLICATION

**Project Overview:**
Quickkart is an advanced E-Commerce Web Application designed for Tailwind Traders to facilitate online shopping for users. The project focuses on integrating the web application and its database with Microsoft Azure to leverage cloud capabilities for improved performance, scalability, automation, and security.

**Problem Statement:**
Tailwind Traders faced several challenges with their existing E-commerce setup:
1. **Performance Issues:** The website experienced slow response times during peak hours.
2. **Automation Needs:** There was a need for automating application development and deployment.
3. **Cost Management:** Efficient management of image storage costs when not in use.
4. **Security and Monitoring:** Ensuring secure handling of confidential data and robust monitoring of the application.

**Project Goals:**
- Integrate Quickkart with Azure to enhance performance and scalability.
- Implement auto-scaling for the website to handle peak traffic.
- Set up a CI/CD pipeline for continuous integration and deployment.
- Adopt a microservices architecture using Platform-as-a-Service (PaaS) offerings.
- Implement cost-effective image storage solutions.
- Enhance security and monitoring using Azure Insights and other tools.

**Technology Stack:**
- **Front-End:** Angular 13
- **Backend:** .NET Core 3.1
- **Database:** Azure SQL Server
- **Blob Storage:** Azure Storage Account

**Detailed Project Tasks:**

**Task 1: Local Environment Setup and Initial Testing**
1. **Set up the Local Environment:**
   - Install Visual Studio Community 2022 with Azure Development SDK.
   - Install .NET Core 3.1, Node.js, Git, and Angular CLI.
2. **Clone Repositories:**
   - Clone the front-end repository from Azure DevOps.
   - Clone the back-end repository, download, and extract it locally.
3. **Database Setup:**
   - Create an Azure SQL database and server.
   - Execute necessary scripts to initialize the database.
4. **Local Testing:**
   - Configure and test the application locally.
   - Ensure the front-end and back-end communicate effectively.
   - Validate the setup by running the Angular application using `ng serve -o` and the .NET application using `dotnet run`.

**Task 2: Implementing Continuous Integration (CI) for Backend**
1. **Build CI Pipeline:**
   - Use Azure DevOps to create a YAML-based CI pipeline.
   - Ensure the pipeline restores packages, builds the application, and publishes artifacts.
2. **Automate Builds:**
   - Configure the pipeline to trigger on changes to the master branch.
3. **Self-Hosted Agent:**
   - Set up a self-hosted Azure DevOps agent on a virtual machine.
   - Install required tools and configure the agent in Azure DevOps.
4. **Pipeline Execution:**
   - Create and configure build pipelines to run on both Microsoft-hosted and self-hosted agents.
   - Validate the build process and ensure artifacts are correctly stored.

**Task 3: Deployment and Monitoring**
1. **Web App Creation:**
   - Create two Azure Web Apps for testing and production environments.
2. **Release Pipeline:**
   - Set up a release pipeline with stages for testing and production.
   - Implement pre-deployment approvals and post-deployment conditions.
3. **Continuous Deployment:**
   - Enable continuous deployment to automate releases based on successful builds.
4. **Monitoring and Alerts:**
   - Set up Azure Monitor alerts and action groups for real-time monitoring.
   - Integrate Azure Key Vault for managing sensitive information.

**Task 4: Implement Login Functionality using Azure Functions**
1. **Develop Azure Function:**
   - Use Visual Studio 2022 to develop a login functionality as an Azure Function.
   - Choose an appropriate trigger for the function.
2. **Deploy Azure Function:**
   - Deploy the function to Azure and configure it to work with the front-end.
   - Update the front-end service to call the Azure Function for login authentication.
3. **CORS Configuration:**
   - Configure Cross-Origin Resource Sharing (CORS) settings to allow the front-end to access the Azure Function.
4. **Testing and Validation:**
   - Test the login functionality to ensure it works correctly with valid credentials.
   - Resolve any issues by checking browser console errors and fixing them via the Azure Portal.

**Benefits:**
- **Enhanced Performance:** Auto-scaling ensures the website handles high traffic efficiently.
- **Streamlined Automation:** CI/CD pipeline automates the development and deployment process.
- **Cost Efficiency:** Cost-effective image storage and resource management reduce operational expenses.
- **Robust Security:** Secure handling of confidential data through Azure Key Vault and secure coding practices.
- **Comprehensive Monitoring:** Real-time monitoring and alerts provide insights and proactive management capabilities.

**Conclusion:**
The Quickkart project exemplifies a thorough approach to building a modern, scalable, and secure E-commerce platform using Microsoft Azure. By leveraging Azure's cloud services, the application benefits from enhanced performance, automation, and security, meeting the client's business requirements effectively.

