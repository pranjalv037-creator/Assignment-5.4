Explanation of CSS Variables


• :root — Defines variables globally so they can be reused throughout the stylesheet.

•  --primary-color — Stores the primary blue color.

•  --secondary-color — Stores the secondary golden color.

•  --background-color — Stores the webpage background color.

•  --text-color — Stores the default text color.

•  --spacing-small, --spacing-medium, • --spacing-large — Store reusable spacing values.

--font-small, --font-medium, --font-large — Store reusable font sizes.

• var(--variable-name) — Uses a previously defined CSS variable.



 Testing Variable Changes


To verify that variables work, open style.css and change:


--primary-color: #24558a;




to:

--primary-color: #287a4b;




Save the file and refresh the webpage. The header, headings, primary buttons, and footer will change to the new primary color automatically.


   



