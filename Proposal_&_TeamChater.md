
**Indian Flavor Scape**

**Proposal:**

Indian Flavor Scape is a restaurant that aims to digitalize the ordering process by providing a web application for customers to select their preferred flavors. Customers can log in, place combination dish orders, and check order status, while staff can view and update orders on the server-side.

**Project Components/Systems/Processes:**

The Architecture of the application divides into 3 main layers:

**User Interface (UI):** Develop an intuitive and user-friendly interface using React.js. This component will allow customers to log in, select their preferred flavors for a combination dish (main + additive1 + side1), place orders, and check order statuses.

**Server-side Backend:** Implement the server-side functionality using Spring Boot. This component will handle user authentication, order management, and communication with the database. It will provide APIs for processing customer orders, updating order statuses, and retrieving order information.

**Database Integration:** Establish a connection with MySQL database to store and retrieve order data. This component will handle the persistence of order details, customer information, and order statuses. It will ensure data consistency and integrity.

**Advanced Data Structure: Queue & Map Implementation:**

To efficiently manage and process customer orders, we will utilize a queue data structure. The queue will store order IDs, representing the order sequence. When a customer places an order, the order ID will be added to the queue. This queue will be utilized to maintain the order sequence and facilitate order processing on the server side.

MAP data structure enables communicating with frontend with JSON’s.

**Project Scope and Time Allocation**

To meet the proposed scope, we will follow an agile development approach, breaking down the project into manageable tasks or User Stories and assigning them to team members accordingly. Regular meetings will be held to track progress, address challenges, and adjust the project plan as needed. The aim is to deliver working software on every sprint.


**Team Charter**

**Project Goal:** 

Our goal is to develop the Indian Flavor Scape web application, which will provide a digitalized ordering process for customers to select their preferred flavors and place combination dish orders, facilitating a client and server login, while allowing staff to view and update orders on the server-side.

**Communication Method:** 

We will primarily communicate through Google Chat for team discussions and updates. Git-Lab issues to address major issues and share project-related information. Additionally, we will utilize email for formal communication and important announcements. Zoom to collaborate virtual support between teams. We will use Kanban Board to manifest the product backlogs. Apart from Tuesday standup we had planned to schedule a meeting on Sunday.

**Scrum Master:** 

Bhanu Prasad Kandula will take on the role of the Scrum Master. He will be responsible for keeping the team meetings on track, facilitating effective communication, coordinating tasks, and scheduling Zoom meetings if necessary.

**Programming Languages:** 

For the back-end processing, we will be using Java in spring boot/hibernate framework. For the front-end development we will use HTML, CSS, Boot Strap java script with React framework. MySQL as database technology.

**Other Considerations:**

We will follow an agile development approach, breaking down the project into manageable tasks or User Stories and assigning them to team members accordingly.

Regular team meetings will be scheduled to track progress, address challenges, and adjust the project plan if necessary.

We will utilize Kanban as our project management tool to track and manage our product backlogs. We will create a Kanban board with different lists representing different stages of the project. Each team member will have access to the Kanban board and will be responsible for updating their assigned tasks and moving them through the appropriate lists.

We will maintain a shared project repository on a version control system GitLab to ensure collaborative development and version management.

Documentation and commenting standards will be established to promote code readability and maintainability.

Testing and quality assurance processes will be implemented to ensure a stable and reliable web application.

Regular updates and progress reports will be shared among team members to foster transparency and accountability.

We will adhere to project timelines and deadlines as agreed upon collectively.

Any conflicts or issues within the team will be addressed openly and resolved in a respectful and constructive manner.

By agreeing to this team charter, we commit to working collaboratively, communicating effectively, and delivering a successful Indian Flavor Scape web application.
