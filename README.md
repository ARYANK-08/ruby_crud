# From Django to Delight: A Rails CRUD App Journey

Detailed Article : [Click Here!](https://github.com/ARYANK-08/aiwitharyan/tree/main/Ruby/ruby%20on%20rails)

Building a CRUD application using Ruby on Rails was easier compared to Django. PS: I enjoyed seeing **Devise** and **scaffold** in Rails doing all the magic for me! 

Ruby on Rails simplifies web development by utilizing the **MVC (Model-View-Controller)** pattern and its philosophy of "convention over configuration." This approach streamlines code and automates common tasks, making it faster and easier for developers to build, maintain, and scale web applications.

## Snapshot
![image](https://github.com/user-attachments/assets/3ed029d2-49c4-42a0-9458-3745797afb17)

## Key Takeaways:

* **MVC Architecture:** Rails strictly adheres to MVC, with clear separation between Models (database interaction), Views (presentation), and Controllers (request handling).
* **Route Configuration:**  `config/routes.rb`  manages URL patterns and their mapping to controllers and actions.
* **Scaffolding Magic:**  `rails g scaffold` is a game-changer! It auto-generates CRUD functionality, saving significant time and effort.
* **Associations:**  Rails makes managing relationships between models (e.g., User has many Friends) incredibly easy.
* **Devise Gem:** User authentication and management are a breeze with the Devise gem.

## Highlights of the Journey:

* **Initial Awe:**  The ease of generating a full-fledged CRUD app with a single command ("What the actual FFFF!!! ????")
* **Convention over Configuration:**  Rails' "automatic car" approach compared to Django's manual configuration.
* **Gem Power:**  Gems like Devise simplify complex tasks like user authentication.
* **Associations Simplified:**  Effortlessly defining and managing relationships between models.

## Code Examples:

* Creating a scaffold: `rails g scaffold Friend first_name:string ...`
* Migrating the database: `rails db:migrate`
* Defining associations: `has_many :friends`, `belongs_to :user`
* Using Devise: `gem 'devise'`, `rails generate devise:install`

## Running the Application

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository-name.git 
   cd your-repository-name 
   ```

   (Replace  `your-username/your-repository-name` with the actual details of your repository).

2. **Install dependencies:**

   ```bash
   bundle install
   ```

3. **Set up the database:**

   ```bash
   rails db:create
   rails db:migrate
   ```

4. **Start the Rails server:**

   ```bash
   rails s
   ```

5. **Access the app:**

   Open your web browser and go to `http://localhost:3000/`. You should now be able to interact with your Rails CRUD application.

