# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web Page with Form, List, Table & Image</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h2>Ordered List</h2>
    <ol type="I">
      <li>Monday</li>
      <li>Tuesday</li>
      <li>Wednesday</li>
      <li>Thursday</li>
      <li>Friday</li>
    </ol>

    <h2>External Image</h2>
    <img
      src="https://images.pexels.com/photos/3183153/pexels-photo-3183153.jpeg"
      alt="Professional Work Setup"
      width="600"
    />

    <h2>Contact List</h2>
    <table border="1">
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Peter Smith</td>
          <td>123 Main St, Cape Town</td>
          <td>+27 123 456 7890</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Park Ave, Johannesburg</td>
          <td>+27 76 555 0001</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>Michael Brown</td>
          <td>789 Ocean Dr, Durban</td>
          <td>+27 79 222 3334</td>
          <td>michael@example.com</td>
        </tr>
        <tr>
          <td>Lisa White</td>
          <td>567 Hill Rd, Pretoria</td>
          <td>+27 72 333 8889</td>
          <td>lisa@example.com</td>
        </tr>
        <tr>
          <td>David Green</td>
          <td>101 Elm St, Port Elizabeth</td>
          <td>+27 78 666 7778</td>
          <td>david@example.com</td>
        </tr>
      </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="POST">
      <label for="name">Full Name:</label>
      <input
        type="text"
        id="name"
        name="name"
        placeholder="Enter your full name"
        required
      />

      <label for="email">Email Address:</label>
      <input
        type="email"
        id="email"
        name="email"
        placeholder="Enter your email"
        required
      />

      <label for="password">Password:</label>
      <input
        type="password"
        id="password"
        name="password"
        placeholder="Enter a strong password"
        required
        minlength="6"
      />

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required />

      <label for="country">Select Country:</label>
      <select id="country" name="country" required>
        <option value="">Choose a country</option>
        <option value="south_africa">South Africa</option>
        <option value="usa">United States</option>
        <option value="uk">United Kingdom</option>
        <option value="canada">Canada</option>
      </select>

      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required />
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" required />
      <label for="female">Female</label>

      <label>Interests:</label>
      <input type="checkbox" id="coding" name="interests" value="coding" />
      <label for="coding">Coding</label>
      <input type="checkbox" id="sports" name="interests" value="sports" />
      <label for="sports">Sports</label>
      <input type="checkbox" id="music" name="interests" value="music" />
      <label for="music">Music</label>

      <button type="submit">Register</button>
    </form>
  </body>
</html>

