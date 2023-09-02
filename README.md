# Rocky-E-Commerce

Rocky-E-Commerce is an innovative e-commerce platform built on the .Net Core MVC framework, utilizing SQL as its underlying database. This project replicates the functionality of a typical e-commerce website, allowing users to browse and purchase various types of rocks, add them to their shopping cart, and complete the checkout process. The application also boasts a robust authentication and authorization system, enabling both customers and administrators to access distinct features.

## Key Features

### Admin Capabilities
- **Comprehensive CRUD Operations**: Administrators have full control over product management, including adding new products, defining product categories, and specifying application types.
- **User Management**: Admins can create additional admin users, granting them the necessary privileges to manage the platform.
- **Admin Dashboard**: A dedicated admin dashboard provides a seamless interface for managing products and users efficiently.

### Customer Experience
- **Home Page**: The website's home page offers a user-friendly interface with tabs for filtering rocks based on various attributes. Users can select items and add them to their shopping cart. However, access to the cart is restricted to authenticated users.
![Home Page](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/ccd84d06-637c-42c7-b855-65ebb07fbcc6)

### User Registration and Authentication
- **User Registration**: New users can easily register on the platform, with their information securely stored in the SQL database. The system employs the .NET Core Identity module for authentication and authorization.
![Registration Page](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/46799c56-9a89-42ce-a046-27c1e42c2823)

- **User Login**: Registered users can access their accounts by providing their email address and password.
![Login Page](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/288d2a0e-3437-4bd9-b2df-87460505aef0)

### Shopping Cart and Checkout
- **Shopping Cart**: Users can view and manage items in their shopping cart. It is also possible to update user details before proceeding to checkout. Once the checkout process is completed, the website's team is notified via email, and the order is processed.
![Shopping Cart](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/223e9a4f-96e4-4e79-b3ea-309de8ee626f)

### Administrator Functionality
- **Admin Operations**: Administrators can create, read, update, or delete product categories, application types, and individual products. These operations are seamlessly integrated into the platform's user interface.
![Admin Operations](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/ace3a981-8a5f-4a27-ae30-a3c042cefa97)

- **Admin Privileges**: Admins can also register other administrators, extending the administrative team as needed.
![Admin Makes Other Admin](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/30df180e-b374-439f-b5e9-ce66697e9fff)

### Access Control
- **Customer Access Restrictions**: Customers attempting to access pages for product management, category creation, or application type management will encounter access denied messages, ensuring data security.
![Customer Access Restrictions](https://github.com/sahil1699/Rocky-E-Commerce/assets/52308072/eae5cc48-80ab-44ff-829a-cd9c6e7011c8)

---

**Final Notes**

Rocky-E-Commerce offers a fully functional e-commerce experience with a rich set of features for both customers and administrators. With its user-friendly interface, secure authentication, and robust product management capabilities, this platform is poised to provide an enjoyable and efficient shopping experience for rock enthusiasts and collectors. Whether you're a customer looking to add unique rocks to your collection or an administrator managing an online rock store, Rocky-E-Commerce has you covered. Explore the world of rocks today!
