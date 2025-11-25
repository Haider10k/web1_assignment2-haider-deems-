Include a list of tasks that need to be completed

- Complete sketches: 2/3 completed
    - Home page (done)
    - Gallery page (done)
    - Contact page (done)

- Website idea:
    - rstimepieces (watch business)
    - offer custom Seiko mods

- Create Home page: 12/12 completed
    - create a header with navigation tab (done)
        - complete styling to sketch standards (done)
    - Introduction image and text (done)
        - complete styling to sketch standards (done)
    - About us (done)
        - complete styling to sketch standards (done)
    - Frequently asked questions (done)
        - complete styling to sketch standards (done)
    - Follow our work (done)
        - complete styling to sketch standards (done)
    - footer (done)
        - complete styling to sketch standards (done)

- Create Gallery page: 10/10
    - create a header with navigation tab (done)
        - complete styling to sketch standards (done)
    - Our Gallery introduction (done)
        - complete styling to sketch standards (done)
    - Timepiece styles [4 images with captions] (done)
        - complete styling to sketch standards (done)
    - What we offer table (done)
        - complete styling to sketch standards (done)
    - footer (done)
        - complete styling to sketch standards (done)

- Structural requirements: 
    - follow validator requirements
    - atleast 3 web pages (done)
    - each page is consistent with one another: 2/2
        - consistent look and feel (done)
        - navigation menu with link to all pages (done)
    - Website must include the following elements: 11/11
        - a logo (done)
        - one photo enclosed in a figure with a figcaption (done)
        - All images in a folder called images (done)
        - define alt attributes (done)
        - appropriate content for each page (done)
        - Meta tags for each page (done)
        - title for each page (done)
        - atleast one html comment (done)
        - one external link to another website that opens in a new tab (done)
        - atleast one link to another place on the same page (done)
        - a table with a merged cell (done)
    - Semantic markup: 2/2
        - Use nav tag (done)
        - use article, header, main, and footer, tags (done)
    - Contact form: 16/16
        - salutation (done)
        - first name (done)
        - last name (done)
        - phone number (done)
        - email (done)
        - subject (done)
        - body (done)
        - controls on input: 5/5
            - use the appropriate input types (done)
            - all fields are required (done)
            - autofocus must be set to the first name (done)
            - include a placeholder phone number to show the valid format and pattern (done)
            - include a placeholder email to show valid format and pattern (done)
        - radio buttons with atleast 2 different options (done)
        - checkboxes with atleast 2 different options to select (done)
        - a reset button (done)
        - a submit button (done)
    - no internal or embedded css (done)
    - Styling requirements: 8/9
        - external style sheets that are linked in the head of the webpages (done)
        - first letter pseudo element selector to style a first letter of atleast one  (done)
          paragraph (done)
        - pseudo class selector in atleast one page (done)
        - contextual selector in atleast one page (done)
        - attribute selector in atleast one page (done)
        - style your table to have striped table format (done)
        - float an image to the right side of a paragraph of your choice 
        - consistent design for the header and footer of all pages (done)
        - all pages must use consistent font, margin, and padding (done)

ASSIGNMENT 2 - PART 2 (accessibility fixes):
- Manual search: 4/4
    1- Improved alt text for our images (done)
        - making our alt text more descriptive so users have a better understanding of what each image is
            - ex. changing our img tag from 
            <img src = "../images/instagram.png" alt = "instagram logo"> 
            -->
            <img src = "../images/instagram.png" alt = "instagram logo linking to rstimepieces_ profile">
    2- Adding a missing table caption (done)
        - Never had a table caption so we added one to ensure there is now a descripion of what our table showcases
            - ex. added the following to our gallery.html file
            <caption>
                Comparison of our Four main custom Seiko Mod styles
            </caption>
    3- Improved form labels (done)
        - ensured that all our labels were descriptive 
            - ex. altered id and for elements in our contact.html file from 
            <input type = "radio" id = "mr" name = "salutation">
            <label for = "mr">Mr.</label>
            -->
            <input type = "radio" id = "Male" name = "salutation">
            <label for = "Male">Mr.</label>
    4- Increased touch point for smaller devices (done)
        - made buttons and navigation links larger in order to make them easier to access on smaller devices
            - ex. altered our submit and reset buttons on the contact form to be larger for devices under 590px
            input[type="submit"], input[type="reset"] {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            box-sizing: border-box;
            }
    5- Add an item focus outline (done)
        - makes it more accessible to see what item a user is interacting with
            - ex. added the following to the globalStyle.css page to effect all pages
            a:focus, button:focus, input:focus, textarea:focus {
                outline: 3px solid rgb(39, 190, 102);
                outline-offset: 2px;
            }
- Automated search: 
