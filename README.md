# Student Information Flask Web Application (Python, MySQL HTML5, CSS, JavaScript, Unit test)


This project is a Python-based web application built using the Flask framework and follows the MVC architecture. It adds a feature allowing users to search records across multiple columns simultaneously.

## Key Features:
- **MVC Pattern**: The application separates data handling (Model), user interface (View), and control logic (Controller).
- **Multi-Column Search**: Users can input search terms for multiple columns (e.g., `ref_number`, `disclosure_group`, `title_en`, etc.) and retrieve filtered results.
- **Database Integration**: Uses MySQL for storing and retrieving travel data, with SQL queries constructed dynamically based on user input.

## Components:
- **Model**: Defines the data structure and database interaction logic (e.g., `RecordDAO.py` for querying and `RecordDTO.py` for data representation).
- **Controller**: Handles user input and business logic, such as processing form submissions and invoking database searches.
- **View**: HTML templates (`index.html`, `search_results.html`) for displaying the records and search results.

## Setup:
1. Clone the repository.
2. Configure the database connection in `Controller.py`.
3. Run the Flask application using:

    ```bash
    flask run
    ```

This feature improves data searching flexibility, allowing users to search records based on multiple criteria at once.

---

*Created by Xin-Jie Huang*
•	Created a robust web application adhering to the MVC design pattern for efficient data management.

•	Implemented Flask, a Python web framework, to streamline functionality and routing.

•	Conducted thorough unit tests to ensure the seamless operation of CRUD functionalities.

