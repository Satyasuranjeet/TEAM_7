# Animated Registration Form

A stylish and animated registration form built using HTML, CSS, and JavaScript. This form includes smooth animations, real-time validation, and a submission process that sends data to a Google Apps Script.

## Features

- **Loader Animation:** The page displays a loader during the initial loading phase.
- **Smooth Appearance:** The registration form smoothly appears with an animation.
- **Real-time Validation:** Input fields validate the user input in real-time and display error messages when the input is invalid.
- **Button Hover Effect:** The submit button has a hover effect with a subtle scale animation.
- **Success Message:** After a successful registration, a success message appears briefly.
- **Responsive Design:** The form is fully responsive and works well on mobile devices.

## Screenshots

### Loader Screen
![Loader Screen](https://i.ibb.co/Rpdg6zHG/image.png)

### Registration Form
![Registration Form](https://i.ibb.co/fVY19Q72/image.png)

## How It Works

1. **Loading Animation:** The loader is displayed initially when the page loads. After a brief delay, it disappears.
2. **Form Inputs:** 
   - **Name:** Requires at least 3 characters.
   - **Mobile:** Must be a valid 10-digit number.
   - **Email:** Requires a valid email address format.
   - **Tech Stack:** A free-form field to enter your tech stack.
   - **Profile Picture URL:** Must be a valid URL.
   - **Github Profile URL:** Must be a valid URL.
   - **Interest & Hobby:** Simple text fields.
3. **Error Messages:** Invalid inputs trigger an error message next to the field.
4. **Form Submission:** Upon submission, a POST request is sent to a Google Apps Script endpoint with the form data. If the submission is successful, a success message appears.

## Installation

Clone this repository to your local machine to use the form:

```bash
git clone https://github.com/yourusername/animated-registration.git
```

Open the `index.html` file in a browser to view and interact with the form.

## Usage

1. Open `index.html` in any modern web browser.
2. Fill out the form fields.
3. Submit the form.
4. If the data is valid, you'll see a success message, and the form will reset.

## Contributing

Feel free to fork this repository and make improvements. You can submit a pull request for any changes you'd like to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
