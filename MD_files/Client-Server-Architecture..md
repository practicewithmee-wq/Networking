# Client-Server Model
The Client-Server Model is a network architecture in which clients send requests for resources or services, and servers process these requests, returning the required responses.   

- **Client**: A device or program that requests data or services (e.g., web browser).
- **Server**: A system that stores resources, manages data, and responds to client requests.
- **Request–response mechanism**: Communication follows a structured cycle — client requests, server responds.
- **Centralized management**: Data and services are controlled from servers, improving security and consistency.

# Working
The client-server model works on a request–response flow where a client requests a service/data and the server processes that request and returns a response

![client](/Images/C-S-M.png)

- Client is a device/app that requests services from a server, like a web browser or email app.
- Server is a system that listens for requests and responds by sending data or performing operations.
- Servers can handle many clients at the same time using concurrent request handling.
- Example client apps include Chrome/Firefox and Gmail/Outlook.
- Example servers include web servers (Apache/Nginx), email servers, and database servers.

## How a Browser Interacts With a Server

![request_and_response](/Images/request_and_response.png)

- User enters a URL in the browser (example: www.example.com).
- Browser performs a DNS lookup to convert the domain name into an IP address.
- Browser establishes a connection and sends an HTTP/HTTPS request to the server using that IP.
- Server responds with website resources like HTML, CSS, JavaScript, and images.
- Browser renders the webpage by processing these files and displaying the content

## Types of Client-Server Architecture  
Client-server architecture is commonly classified by how many layers handle presentation, logic, and data.

2-tier architecture links the client directly to the database, offering simple, fast performance for small-scale applications.

3-tier architecture inserts an application server between them, separating presentation, business logic, and data storage.

## 2-Tier Architecture    
In a 2-tier setup, the system is structured as a basic client-server model. Application logic is placed directly in the client interface or buried inside the database on the server.

- **Structure**:
    - **Client Tier**: The user interface (UI) and local application.
    - **Data Tier**: The database management system.
- **How it works**: The client connects directly to the database (usually via APIs like ODBC or JDBC).
- **Best Use Cases**: Small business software, localized contact management systems, or prototypes.
- **Pros**: Lower cost, easier deployment, and faster direct data retrieval for a small number of users.
- **Cons**: Becomes sluggish with many users, presents higher security risks (since clients have direct database access), and is difficult to scale.

## 3-Tier Architecture
3-tier architecture physically and logically separates the system into three distinct processing nodes or layers, keeping the business logic independent from both the UI and data.

- **Structure**:
    - **Presentation Tier (Client)**: The user interface, such as a web browser or mobile app.
    - **Application Tier (Middle)**: The engine where all business logic, data processing, and application rules happen.
    - **Data Tier**: The backend database or storage system.
- **How it works**: The client talks exclusively to the application server. The application server processes the request and communicates with the database to fetch or update data.
- **Best Use Cases**: Complex web applications, e-commerce sites, enterprise software, and systems distributed over the internet.
- **Pros**: Highly scalable, more secure (clients do not access the database directly), and much easier to update or maintain.
- **Cons**: Higher initial setup cost, more complex to design, and requires more network overhead.
