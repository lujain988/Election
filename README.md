# Election Website Project

## Overview

Welcome to the National Voting System(NVS)! this platform is designed to facilitate the entire electoral process, providing functionalities for voters, candidates, and administrators. The system allows users to participate in elections, submit nominations, and manage election-related data efficiently.

## Features

- **Home Page:** Includes a summary of services, an image slider with election-related content, and footer information.
- **Results Page:** Displays election results by governorate with details on winning candidates.
- **Candidate Nomination:** Enables candidates to submit nomination requests and make payments via PayPal or Stripe.
- **Voting System:** Allows voters to log in, vote for local or party lists, and view results after the voting period ends.
- **Admin Dashboard:** Provides tools for managing users, candidates, and election processes.
- **Additional Features:**
  - Live voting percentage broadcasts.
  - Candidate debates via Zoom links.
  - Email confirmations for the contact us page.
  - Optional chat functionality between admin and users.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap 5
- **Backend:** C#, ASP.NET MVC
- **Database:** SQL Server
- **Version Control:** Git

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/lujain988/Election.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd election-website
   ```

3. **Setup the Database:**

   - Open SQL Server Management Studio.
   - Execute the SQL scripts in the `Database` folder to create the necessary tables and relationships.

4. **Add Database in model:**

   - Add database in model to set up the initial schema:

5. **Run the Application:**

   - Start the application in Visual Studio or using the command line:

     ```bash
     dotnet run
     ```

   - Access the application at `http://localhost:5000`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for checking out the Election Website project. We hope this platform enhances the electoral experience for all users. If you have any questions or feedback, please feel free to contact us.
