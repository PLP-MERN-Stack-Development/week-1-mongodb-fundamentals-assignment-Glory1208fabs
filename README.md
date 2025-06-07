[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19725451&assignment_repo_type=AssignmentRepo)

To run the scripts in this project, follow these steps:

1. **Install Dependencies**

   Make sure you have [Node.js](https://nodejs.org/) installed. Then, install the required dependencies by running:

   ```sh
   npm install
   ```

2. **Start MongoDB**

   Ensure your MongoDB server is running locally on `mongodb://localhost:27017`.

3. **Insert Sample Books**

   Run the following command to populate the database with sample book data:

   ```sh
   node insert_books.js
   ```

   You should see a message confirming that books were successfully inserted.

4. **Run MongoDB Queries**

   Open the `queries.js` file and execute the queries using the MongoDB shell (`mongosh`) or MongoDB Compass as needed.  
   You can copy and paste the queries directly into your MongoDB shell.

---