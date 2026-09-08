# Student Voice — School Feedback Portal

**Student Voice** is a modern and responsive school feedback website that gives students a simple way to share **suggestions, complaints, and concerns** with their school.

The website is designed with a clean, professional interface and can be connected to a backend/API for storing feedback.

## Features

* Clean and modern responsive UI
* Student suggestion and complaint system
* Separate **Suggestion** and **Complaint** options
* Student name and class/section fields
* Feedback categories
* Priority selection
* Detailed feedback message
* Anonymous submission option
* Feedback submission confirmation
* Mobile, tablet, and desktop responsive design
* School illustration on the homepage
* Interactive navigation between Home and Feedback pages
* Backend/API integration can be added later

## Technologies Used

* **HTML5** — Website structure
* **CSS3** — Styling, responsive design, gradients, cards and layout
* **JavaScript** — Page navigation, form interaction and submission handling
* **SVG** — Website illustrations and icons

## Project Structure

```text
Student-Voice/
│
├── index.html
├── style.css
│
├── school-illustration.svg
├── suggestion-icon.svg
├── complaint-icon.svg
└── privacy-icon.svg
```

> Make sure the SVG files are uploaded to the same GitHub repository/folder as `index.html` if they are referenced using filenames such as `school-illustration.svg`.

## How It Works

### 1. Homepage

Students are welcomed with a short introduction explaining the purpose of the Student Voice portal.

They can choose:

* **Give a Complaint / Suggestion**
* **Learn More**

### 2. Feedback Form

Students can select whether they want to submit a:

* Suggestion
* Complaint

They can then provide information such as:

* Student Name
* Class & Section
* Category
* Priority
* Subject
* Feedback Details

Students can also select **Submit anonymously**.

### 3. Submission

After submitting the form, a confirmation message is displayed.

Currently, the project contains the **frontend form**. A backend/API can be connected later to permanently store submissions.

## Feedback Categories

The portal currently supports categories including:

* Academics
* Teachers
* Infrastructure
* Cleanliness
* Canteen
* Sports
* Transport
* School Events
* Safety
* Other

## Responsive Design

The website is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile phones

CSS media queries automatically adjust the layout for smaller screens.

## Backend

The current version is a frontend project.

To permanently save feedback, a backend/database can be connected to the form using an API.

Possible future backend features include:

* Secure feedback storage
* Admin dashboard
* Feedback status tracking
* Student authentication
* Anonymous feedback handling
* Search and filtering
* Analytics and statistics

## Running the Website Locally

1. Download or clone this repository.
2. Keep all HTML, CSS and SVG files in the correct locations.
3. Open `index.html` in a web browser.

For GitHub Pages, upload the project files to your repository and enable **GitHub Pages** from the repository settings.

## Future Improvements

Planned improvements could include:

* Admin dashboard
* Database integration
* Login system
* Email notifications
* Feedback tracking
* Admin response system
* Feedback analytics
* Dark mode
* More accessibility improvements

## Credits

Created as a school web-development project to provide students with a simple and organized way to communicate their ideas and concerns.

## License

This project is intended for educational and personal project use.
