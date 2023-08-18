1. Name Project : Website shopping online BIS STORE
2. How to install :
  -  Prerequisites:
      +  Java JDK (recommended version 11 or above)
      +  Maven (for managing dependencies)
      + MySQL Server (recommended version 5.7 or above)
- Step 1: Clone the Project from GitHub
      + Open Terminal or Command Prompt.
      +  Run the following command to clone the project from GitHub:
  
  ======================================================================================== 
git clone https://github.com/lamnguyenfda/ShopingOnline.git
  ======================================================================================== 
  
    + Navigate to the project directory:

 ======================================================================================== 
  cd MultiShop
 ======================================================================================== 
- Step 2: Configure the Database
   + Open SQL Server.
   + Create a new database with the name "MuLtiShop".
   + Update the database configuration information in the src/main/resources/application.properties file:
     
======================================================================================== 
spring.datasource.driver-class-name=com.microsoft.sqlserver.jdbc.SQLServerDriver
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=MuLtiShop;encrypt=true;trustServerCertificate=true;
spring.datasource.username=your-sql-username
spring.datasource.password=your-sql-password
======================================================================================== 

Step 3: Build and Run the Application
    +  Open Terminal or Command Prompt in the project directory.
    +  Run the following command to build the application and install its dependencies:
     
  ======================================================================================== 
     mvn clean install
  ========================================================================================
  
  + Run the application using the command:

========================================================================================
mvn spring-boot:run
========================================================================================

   + The application will start running at the address http://localhost:8080/index

Step 4: Access the Application
  +  Open a web browser and visit the address [http://localhost:8080](http://localhost:8080/index) to view your online Bis Store web application.

3.the main features 
- Đăng nhập (Login): Users can log in to their accounts using their credentials.
- Đăng xuất (Logout): Logged-in users can log out from their accounts.
- Tìm kiếm sản phẩm (Product Search): Users can search for products using keywords.
- Xem chi tiết sản phẩm (View Product Details): Users can view detailed information about a specific product.
- Xem thông tin người dùng (View User Information): Users can view their personal information and account details.
- Nhận xét và đánh giá sản phẩm (Product Reviews and Ratings): Users can leave reviews and ratings for products.
- Quản lý giỏ hàng (Cart Management): Users can add products to their cart, update quantities, and remove items.
- Quản lý thông tin cá nhân (Profile Management): Users can edit and manage their personal information.
- Xem danh sách các sản phẩm đề xuất (View Recommended Products): Users can see a list of recommended products based on their preferences or browsing history.
- Phân trang sản phẩm (Product Pagination): Product lists are split into pages to improve navigation.
- Lọc các sản phẩm theo giá cả (Filter Products by Price): Users can filter products based on price ranges.
- Quản lý sản phẩm (Product Management): Admin users can manage products, including adding, editing, and deleting products.
- Quản lý thương hiệu (Brand Management): Admin users can manage brands associated with products.
- Quản lý danh mục (Category Management): Admin users can manage product categories.
- Xem danh sách đơn hàng (View Order List): Users can view their order history and details.
- Xem danh sách mã giảm giá (View Discount Codes): Users can see a list of available discount codes
- Quản lý bài viết (Article Management): Admin users can manage blog articles and posts.
- Phản hồi người dùng (User Feedback): Users can provide feedback and comments on products or the website.

