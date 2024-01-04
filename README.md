# SARS School Management React Frontend

Welcome to the SARS School Management React Frontend repository! This React-based frontend complements the Express.js and MongoDB backend for a comprehensive school management system.

## Project Structure

The project structure consists of the following directories and files:

- **public**: Contains public assets and HTML files.
  - **assets**: Includes static assets.
    - **img**: Stores images used in the application.
      - **avatars**: Collection of avatar images (1.jpg, 2.jpg, ..., 8.jpg).
- **src**: Main source code directory.
  - **assets**: Static assets used in the application.
    - **img**: Images used in the application.
      - **avatars**: Avatar images.
  - **containers**: React components organized by functionality.
    - **SSRSHome**: Components related to the home page.
  - **redux**: Redux state management configuration.
    - **Admin**: Redux actions and reducers for admin-related functionality.
    - **Faculty**: Redux actions and reducers for faculty-related functionality.
  - **scss**: SCSS stylesheets.
    - **vendors**: SCSS styles related to vendor-specific styling.
      - **_variables.scss**: Variables for SCSS styling.
  - **ssrsview**: React components representing different views in the application.
    - **Admin**: Components related to the admin view.
    - **CommanPages**: Common pages shared across different roles.
    - **Faculty**: Components specific to faculty view.
    - **Student**: Components specific to student view.
  - **redux**: Redux state management configuration.
    - **Admin**: Redux actions and reducers for admin-related functionality.
    - **Faculty**: Redux actions and reducers for faculty-related functionality.
  - **scss**: SCSS stylesheets for styling the components.
    - **vendors**: Vendor-specific SCSS styles.
  - **ssrsview**: React components representing different views.
    - **Admin**: Components for the admin view.
    - **CommanPages**: Common pages for different roles.
    - **Faculty**: Components specific to the faculty view.
    - **Student**: Components specific to the student view.

## Components Overview

### SSRSHome

- **Header.js**: Header component for the home page.
- **Footer.js**: Footer component for the home page.
- **Home.js**: Main content component for the home page.
- **about.js**: Component containing information about the application.
- **termsconditions.js**: Component displaying terms and conditions.

### Redux Configuration

#### Admin

- **AdminAction.js**: Redux actions for admin functionality.
- **AdminReducer.js**: Redux reducer for admin functionality.
- **AdminType.js**: Redux action types for admin.

#### Faculty

- **ConfirmRegReducer.js**: Redux reducer for confirming registration.
- **FacultyReducer.js**: Redux reducer for faculty functionality.
- **GetProfileReducer.js**: Redux reducer for fetching profiles.
- **updateProfileReducer.js**: Redux reducer for updating profiles.
- **FacultyAction.js**: Redux actions for faculty functionality.
- **FacultyType.js**: Redux action types for faculty.

### SCSS Styling

- **_custom.scss**: Custom styling for the application.
- **_ie-fix.scss**: Styling fixes for Internet Explorer.
- **_variables.scss**: SCSS variables.
- **style.scss**: Main SCSS file.
- **vendors/_variables.scss**: Vendor-specific SCSS variables.

## Usage

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd SARS-School-Management-React-Frontend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.