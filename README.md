# Password Generator

## Overview
This project is a simple and interactive web-based **Password Generator** that allows users to create secure and customizable passwords. Users can specify the length of the password and choose whether to include uppercase letters, lowercase letters, numbers, and symbols.

## Features
- Dynamically generate strong and secure passwords.
- Options to include or exclude:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- Adjustable password length between 4 and 20 characters.
- Copy generated password to the clipboard with a single click.
- Clean and responsive design.

## Technologies Used
### Frontend
- **HTML5**: Structure of the webpage.
- **CSS3**: Styling and layout of the webpage.
  - Includes external CSS from [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css) for icons.
- **JavaScript**: Core functionality to handle password generation and user interactions.

## File Structure
```
Password-Generator/
|-- index.html      # Main HTML file
|-- style.css       # CSS file for styling
|-- script.js       # JavaScript file for functionality
```

## How to Use
1. **Open the Application**: Load the `index.html` file in any modern web browser.
2. **Customize Settings**:
   - Set the desired password length using the number input.
   - Toggle the inclusion of uppercase letters, lowercase letters, numbers, and symbols using the checkboxes.
3. **Generate Password**: Click the **Generate Password** button to create a password.
4. **Copy Password**: Click the clipboard icon to copy the generated password to your clipboard for easy use.

## External Libraries
- **Font Awesome**: Used for the clipboard icon.
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css" integrity="sha512-1PKOgIY59xJ8Co8+NE6FZ+LOAZKjy+KY8iq0G4B3CyeY6wYHN3yt9PW0XpSriVlkMXe40PTKnXrLnZ9+fkDaog==" crossorigin="anonymous" />
  ```

## Future Improvements
- Add strength indicators for generated passwords.
- Provide an option to save generated passwords securely.
- Enhance the UI for better user experience.

## License
This project is open-source and available for modification and distribution under the MIT License.

---

Feel free to contribute or report issues to make this project better!

