# Survey Form

## Description
This is a user-friendly and responsive survey form that collects user information and preferences. The form ensures data validation and provides a smooth user experience.

## Features
- **Page Title:** The page includes a title with an `h1` element having the ID `title`.
- **Short Explanation:** A paragraph element with the ID `description` provides a brief explanation of the form.
- **Form Element:** The main form has the ID `survey-form` and includes:
  - A text input field for name with an ID of `name` and a corresponding label `id="name-label"`.
  - An email input field with an ID of `email` and a corresponding label `id="email-label"`.
  - A number input field with an ID of `number` and a corresponding label `id="number-label"`.
  - A dropdown menu with an ID of `dropdown` and at least two options.
  - Radio buttons for selecting a single option from a group.
  - Checkboxes for selecting multiple options.
  - A textarea for additional comments.
  - A submit button with an ID of `submit`.

## Validation
- The email input field validates proper email formatting.
- The number input field accepts only numeric values and enforces a defined range using `min` and `max` attributes.
- HTML5 validation messages are displayed for invalid inputs.

## Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/<twizerevincent>/Survey-Form.git
