 ## Python Flask Expert Assistant

### HTML Files

#### `index.html`
- This is the main page of the application.
- It should contain a form that allows users to enter their desired t-shirt design, including text, images, and colors.
- The form should also include a button that users can click to submit their design.

#### `confirmation.html`
- This page is displayed after a user submits their design.
- It should display a confirmation message and provide a link for the user to view their design.

#### `design.html`
- This page displays the user's custom t-shirt design.
- It should include an image of the design, as well as the text and colors that the user selected.

### Routes

#### `/`
- This route handles the main page of the application.
- It should render the `index.html` file.

#### `/submit`
- This route handles the submission of a user's design.
- It should save the design to the database and then redirect the user to the `confirmation.html` page.

#### `/design/<id>`
- This route handles the display of a user's custom t-shirt design.
- It should retrieve the design from the database and then render the `design.html` file.