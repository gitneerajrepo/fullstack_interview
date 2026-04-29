# fullstack_interview
full stachkterview questions

**Beginner**
1 What is full-stack development?
Full-stack development refers to the practice of building and maintaining both the frontend and backend of a web application or web service. A full-stack developer works across all layers of the application, ensuring seamless functionality from the user interface to the server and database.
Key aspects of full-stack development include:
Frontend Development: 
Backend Development: 
Databases and Storage: 
DevOps and Deployment: 


2 difference between client-side and server-side programming
The client-side and server-side refer to two distinct parts of a web application that work together to deliver functionality to users. Understanding their roles is essential for building efficient and responsive applications.
client-side:
This is the part of the application that runs in the user’s browser. It handles user interfaces and interactions, allowing users to see and interact with the application.
server-side:
This part operates on the server and processes requests from the client, performing tasks like database queries, business logic, and serving responses.

3 purpose of HTML, CSS, and JavaScript in web development?
HTML: Defines the structure and content of a webpage.
CSS: Styles the webpage (colors, layout, fonts).
JavaScript: Adds interactivity and dynamic behavior to the webpage.


4 What is a REST API, and why is it used?
A REST API (Representational State Transfer Application Programming Interface) is a standardized way for applications to communicate over HTTP by following a set of principles. It allows clients (like web browsers or mobile apps) to interact with servers to perform operations like fetching or modifying data.
Key Features of a REST API:
Stateless Communication: 
Resource-Based: 
HTTP Methods:
Structured Responses:

Interoperability: REST APIs enable communication between different systems and platforms, making them ideal for building web services.
Scalability: They are stateless, allowing them to handle more traffic with horizontal scaling.
Ease of Use: Clear structure and standard conventions make it easy for developers to understand and implement.
Flexibility: Suitable for a variety of clients, from web applications to mobile and IoT devices.

5 What is the purpose of the div and span tags in HTML?
<div>: This is a block-level element that groups other block-level elements (layout or sections) together. It’s quite useful for layout definition.

<span>: This inline element is great for grouping together other inline elements, such as text nodes. Because the <span > has no structural impact on the content when used, it’s perfect for styling text (or even sections of a larger text) without visually affecting it (other than the actual CSS applied).

6 What are CSS selectors, and can you name a few types?
CSS selectors are patterns used to select and style specific elements in an HTML document. They define which elements a set of CSS rules should apply to, making them a fundamental part of designing the appearance of web applications and user interfaces.

Selectors allow you to target elements precisely, enabling you to control layout, colors, fonts, and other visual aspects of your website. They are essential for creating structured and maintainable CSS code.

**There are different types of selectors, categorized based on what they target:**
1. Elements
2. Classes
3. ID
4. Attribute
5. Descendant: Another way to target other elements is to target them based on the parent element. This method works with any combination of the above, so you can potentially target elements using a specific class that are descendants of an element with a specific attribute value (or any other combination you can think of). Example: div p {}


7 How does JavaScript manipulate the DOM?
**JavaScript accesses and modifies the DOM using methods like:**
Get elements: document.getElementById("id"), querySelector(".class").
Modify content: element.innerHTML = "New Content".
Change styles: element.style.color = "blue".
Add/remove elements: appendChild(), removeChild().

8 What is the difference between relational and non-relational databases?
**Relational: ** Stores data in structured tables with rows and columns (e.g., MySQL, PostgreSQL). Good for relationships and complex queries.
**Non-relational: ** Stores data in flexible formats like documents, key-value pairs, or graphs (e.g., MongoDB, Redis). Better for unstructured or hierarchical data.

**9 How would you handle user authentication in a web application?**
There are many ways to handle authentication, from simple auth, all the way to oAuth. The right option depends on your particular business needs.
A classical example is using JWT for authenticating a website with a RESTful API using the following process:
Frontend: Present a login form to collect credentials from the user.
Backend: Verify credentials against a database and if they’re valid, create a signed token and return it in the response.
Secure connection: From this point on, the frontend will send the token on every request and the backend will validate it to ensure it’s a valid and authenticated user.
Secured best practices: Ensure your passwords are hashed (e.g., with bcrypt) and use HTTPS for a secured data transmission channel.

**10 What is the purpose of package.json in a Node.js project?**
The package.json file in a Node.js project has multiple uses. It defines the project's metadata, like its name, version, and description. It also lists the dependencies and devDependencies required to run or develop the application, as well as scripts for tasks like building, testing, or running the app (and any custom script you’d like to add).

Finally, it ensures reproducible installations by allowing the npm install command to pull consistent dependencies, ensuring you can easily port your project into other systems.

11 What are environment variables, and how are they used?
Environment variables store configuration values (e.g., API keys, database URLs) outside the codebase. This is important for two main reasons:

Security. By extracting these values (which tend to be private) from the codebase, you avoid potential code leaks from becoming a bigger security problem.

More flexible deployments. If these values need to change, by having them as environment variables you don’t need to re-deploy your code, you just need to reload those values (either by restarting the app, or hot reloading the values from a file).


**Intermediate Level**

