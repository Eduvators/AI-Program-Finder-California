
# California AI Program Finder

## 🚀 Description

This project is a web-based tool designed to help users discover, filter, and explore Artificial Intelligence (AI) educational programs offered by universities, colleges, and other institutions across California. It features a curated list of programs, including Eduvators' own certifications, with direct links for further information.

This tool was developed for Eduvators to provide a valuable resource for individuals seeking AI education in California.

## ✨ Features

* **Comprehensive Program Listing**: Browse an extensive list of AI-related degrees, certificates, courses, and workshops.
* **Advanced Search**:
  * Filter by City/Region or Institution name.
  * Filter by Program Type (e.g., Certificate, Degree Program, Courses).
  * Filter by Level (e.g., Undergraduate, Graduate, Professional).
* **Quick Filters**: Easily apply common filters:
  * For Educators
  * Potentially Free programs
  * Online Only options
  * Evening Classes
* **Sorting Functionality**: Sort the displayed programs by:
  * Title (A-Z, Z-A)
  * Relevance (prioritizes featured and highly-rated programs)
  * Price (Low to High, High to Low)
  * Duration
  * Rating
* **Direct Links**: "Learn More" links navigate to the specific program pages or relevant institutional pages.
* **Responsive Design**: Adapts to various screen sizes for usability on desktops, tablets, and mobile devices.
* **Eduvators Branding**: Incorporates Eduvators' branding colors for a cohesive look and feel.

## 🔧 How to Use / View

1. **Live Version (GitHub Pages - Recommended)**:
   * This project can be easily hosted using GitHub Pages. Once set up, the live version can be accessed at:
     `https://[YOUR_GITHUB_USERNAME].github.io/[YOUR_REPOSITORY_NAME]/`
   * (Replace `[YOUR_GITHUB_USERNAME]` and `[YOUR_REPOSITORY_NAME]` with your actual GitHub username and repository name).
   * Ensure your GitHub Pages is set to deploy from the correct branch (usually `main` or `master`) and folder (usually `/root`).

2. **Local Version**:
   * Clone or download this repository.
   * Open the `index.html` file directly in your preferred web browser.

## 💻 Technology Stack

* **HTML5**: Structure of the web page.
* **CSS3**: Styling (embedded within the HTML file).
* **JavaScript (ES6+)**: Client-side logic for filtering, sorting, and displaying programs (embedded within the HTML file).

## 📊 Data Source

The program information displayed is embedded directly within the `index.html` file in the `allSamplePrograms` JavaScript array. This data was compiled from lists provided by Dr. Wolzinger and research conducted as of **May 2025**. It includes a variety of programs from:

* Research Universities
* California State Universities (CSUs)
* Private Institutions
* Community Colleges
* Eduvators' own certifications

**Note**: Program details such as URLs, price, and duration are subject to change by the institutions. The data reflects the information available at the time of compilation.

## 🔮 Future Enhancements (Potential Ideas)

* **Backend Integration**: Migrate program data to a backend database (e.g., Firebase, Supabase, or a custom API) for easier updates, scalability, and management.
* **User Accounts/Favorites**: Allow users to create accounts and save favorite programs.
* **Advanced Text Search**: Implement keyword search within program descriptions and titles.
* **Map View**: Visualize program locations on an interactive map.
* **Visual Grouping by Category**: Display programs grouped by their categories (e.g., Research Universities, CSUs) on the results page.
* **Contribution/Suggestion Form**: Allow users to suggest new programs or corrections.

## 📝 To-Do / Known Issues

* **Data Maintenance**: Program information (especially URLs, price, and duration) requires periodic review and updates to maintain accuracy.
* **Placeholder Details**: Some programs have generic placeholders for fields like "Price" ("Check Website") or "Duration" ("Varies") due to the dynamic nature of this information.
* **Detailed Descriptions**: Program descriptions are currently brief; more detailed information could be added over time.

---

This README should give visitors a good overview of your project! Remember to update the GitHub Pages link if you decide to host it there.
