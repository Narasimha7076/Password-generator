# Password Generator

This is a simple Password Generator application built using React. The application allows users to generate a password of a specified length and include numbers and special characters as per their preference. Users can also copy the generated password to the clipboard with a single click.

## Features

- Generate a random password of customizable length.
- Option to include numbers in the generated password.
- Option to include special characters in the generated password.
- Copy the generated password to the clipboard.

## Technologies Used

- React
- JavaScript
- HTML
- CSS (with TailwindCSS)

### State Variables

- `length`: Stores the length of the generated password.
- `numberAllowed`: Boolean state to include numbers in the password.
- `charAllowed`: Boolean state to include special characters in the password.
- `password`: Stores the generated password.

### React Hooks

- `useState`: Used to manage the state variables `length`, `numberAllowed`, `charAllowed`, and `password`.
- `useEffect`: Calls `passwordGenerator` whenever the `length`, `numberAllowed`, or `charAllowed` states change.
- `useCallback`: Used to memoize the `passwordGenerator` and `copyPasswordToClipboard` functions to avoid unnecessary re-renders.
- `useRef`: Used to reference the password input field for copying the password to the clipboard.

### Functions

- `passwordGenerator`: Generates a random password based on the selected options and length.
- `copyPasswordToClipboard`: Copies the generated password to the clipboard.



