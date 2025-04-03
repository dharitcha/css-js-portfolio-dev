# Frontend Challenge - Porfolio Project

## Overview
This project was developed as part of the Frontend Specialization Challenge within the Alura and Oracle Next Education (ONE) program. The main objective was to deepen CSS knowledge, particularly focusing on **Flexbox** and **responsive layouts**, while integrating JavaScript to enhance interactivity.

The project was built from scratch using an **HTML structure provided**, along with a Figma design suggestion. However, I heavily customized the design, featuring a unique color palette and fully edited elements to achieve a consistent and harmonious appearance.

## Features
- **Responsive Layout:** Designed with Flexbox for adaptability across different screen sizes.
- **Form Validation:** Real-time validation for required fields (name, email, subject, message).
- **Email Validation:** Uses regex to ensure valid email addresses.
- **Character Limits:** Prevents overly long inputs for better usability.
- **Dynamic Button State:** The submit button is disabled until all fields are filled.
- **Form Submission Handling:** Displays alerts for success or errors.

## Technologies Used
- **JavaScript**: Form validation, event handling, and interactivity.
- **HTML**: Structuring the contact form and layout.
- **CSS**: Styling and responsive design with Flexbox.

## How It Works
### Form Validation
- Name and Subject: Cannot be empty, limited to 50 characters.
- Email: Must match a valid email format.
- Message: Cannot be empty, limited to 300 characters.
- If any field is invalid, an error message is displayed below the respective input.

### Dynamic Button State
- The submit button remains disabled until all required fields are correctly filled.
- Input fields trigger validation on user interaction.

### Form Submission
- If all validations pass, the form displays a success alert (`Mensagem enviada!`) and reloads the page.
- If validation fails, an error alert is shown (`Ocorreu um erro, confira os seus dados`).

## Installation and Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/dharitcha/frontend-challenge.git
   ```
2. Open `index.html` in a web browser.
3. Fill out the form and test the validation system.

## Future Improvements
- Implement server-side form submission with backend integration.
- Add animations for better user experience.
- Improve accessibility with ARIA attributes.
- Expand validation with additional security measures.

## Live Demo
You can access the live version here: [dharacastilho.com](https://dharacastilho.com/)

## License
This project is open-source and available under the MIT License.

