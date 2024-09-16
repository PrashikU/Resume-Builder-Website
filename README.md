# Resume-Builder-Website - (Angular)

# Resume Management System

Welcome to the **Resume Management System**! This Angular application allows regular users to submit and view their resumes and provides an admin interface to view a list of all submitted resumes.

## Features

- **Resume Form**: Capture personal details, qualifications, and experiences with dynamic rows.
- **Resume View**: Display a formatted view of the candidate's resume.
- **Admin Dashboard**: View and manage all submitted resumes in a tabular format.

## Screens

### Screen 2: Regular User - Resume Form 📝

After a successful login, users will see a form to either fill out a new resume or edit a previously saved one. 

**Fields to Capture:**
- **First Name** (max 30 characters)
- **Last Name** (max 30 characters)
- **Date of Birth** (minimum age 18 years)
- **Photograph URL**: A URL pointing to the candidate's image.
- **Summary**: A text area with support for bold and italics using markup (`*bold*`, `_italics_`). Example:


- **Qualification**: Dynamic rows for qualifications (max 6). Add (`✚`) and remove (`✘`) rows.
- **Experience**: Dynamic rows for experiences (max 6). Add (`✚`) and remove (`✘`) rows.
- **Submit Button**: Finalizes the form submission.

### Screen 3: Regular User - Resume View 👁️

Displays a final view of the candidate's resume. The view includes:
- **Full Name**
- **Date of Birth**
- **Summary**
- **Qualifications**
- **Experience**

Example format:



### Screen 4: Admin User - Resume List 📋

Displays a tabular view of all submitted resumes, sorted by candidate’s name. Each row includes:
- **Candidate Name**
- **Date of Birth**
- **Last Updated At**
- **Photograph**

**Features:**
- Pagination: Display 5 resumes per page.
- Use Angular pipe directives for date formatting.

## Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/resume-management-system.git
    cd resume-management-system
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Run the Application**:
    ```bash
    ng serve
    ```

4. **Access the App**: Open your browser and go to `http://localhost:4200`.

## Dependencies

- **Angular**: Framework used for building the application.
- **FontAwesome**: For icons. Free version used for `✚` (add) and `✘` (remove) icons.
- **ngx-bootstrap**: For pagination and UI components.

## Validation and Formatting

- **Date Validation**: Ensure the date of birth is at least 18 years old.
- **Text Formatting**: Implement bold and italic text in the summary using Angular pipes or custom directives.
- **Image Validation**: Ensure URLs point to valid images.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For any issues or feature requests, please open an issue in the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Angular team for their framework.
- Thanks to FontAwesome for providing useful icons.

---

Feel free to modify the content to better fit your project's specifics or to include additional information as needed!

