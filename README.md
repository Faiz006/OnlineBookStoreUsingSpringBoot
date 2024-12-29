# OnlineBookStoreUsingSpringBoot

This project is a Java-based e-commerce application designed for book enthusiasts, allowing users to explore, shop, and order books seamlessly. The application is built with a robust back-end powered by Spring Boot, Maven, and an H2 database, ensuring reliability and efficiency. It also includes an admin panel for managing the inventory and categories.
How It Works
1.	Home Page:
o	The application starts with a dynamic home page that displays six books randomly selected from the database.
o	These books change with every page refresh, providing a fresh browsing experience.
2.	Navigation:
o	The navbar provides easy access to various sections:
	Home: Returns users to the homepage.
	Shop: Offers a categorized view of books by genres, formats, or other classifications.
	Cart: Displays selected items for review before purchase.
3.	Shop Section:
o	Books are organized into multiple categories, simplifying browsing for users.
o	Clicking on a book opens a detailed product page displaying:
	Book title, author, and description.
	Page count and other specifications.
	An "Add to Cart" button to include the book in the shopping cart.
4.	Cart and Checkout:
o	The cart section lists all selected items for review, along with pricing details.
o	Users can proceed to the checkout page to complete their purchase.
	During checkout, users enter their name, address, and other required details.
	A QR code is generated for UPI payments.
	After making the payment, users provide the transaction ID and click "Checkout" to finalize their order.
o	All order data, including transaction details, is stored in the H2 database for record-keeping.
5.	Admin Panel:
o	A dedicated admin page allows authorized users to log in and manage the store.
o	Admins can:
	Add or edit book categories.
	Upload new products or update existing ones.
	Oversee orders and user activity.
Key Features
•	Dynamic Content: A constantly refreshing book list on the homepage.
•	Categorized Book Browsing: Intuitive shop section with detailed product pages.
•	Cart and Checkout Workflow: Simple and secure process for reviewing and purchasing books.
•	Admin Controls: Robust management tools for inventory and category updates.
•	H2 Database Integration: All user data, product details, and transactions are securely stored.
Technologies Used
•	Spring Boot: Backend framework for application logic.
•	Maven: Build and dependency management.
•	H2 Database: Lightweight, in-memory database for development and testing.

