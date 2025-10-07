# TASK
##  Planned Approach and Architecture

The project follows the **MERN architecture** with **MySQL** as the database.
Frontend (React.js) interacts with the backend (Node.js + Express.js) through REST APIs.
The backend handles ROI simulations, stores scenarios in MySQL, and generates gated reports.

---

##  Technologies, Frameworks, and Database

* **Frontend:** React.js, Axios, Tailwind CSS
* **Backend:** Node.js, Express.js, dotenv, cors
* **Database:** MySQL (via Sequelize ORM)
* **Other Tools:** pdfkit/puppeteer for PDF generation

---

##  Key Features and Functionality

* Interactive ROI calculator with instant results
* CRUD operations to save, view, and delete scenarios
* Email-gated report generation in PDF or HTML format
* Positive ROI ensured through backend bias logic
* Responsive single-page UI with real-time updates
