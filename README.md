# she-can-foundation-fullstack
Full Stack Internship Task for She Can Foundation

She Can Foundation - Simple Website Project
This is a simple, beautiful website made for the She Can Foundation (an NGO that helps women).

🛠️ How Does It Work? (The 3 Main Parts)
To make a website, we need three basic things:
HTML (The Skeleton/Bones): This creates the actual text, buttons, text boxes, and structure of the website.
CSS (The Clothes/Design): This makes the website look modern, colorful, neat, and professional. (We used Tailwind CSS, which lets us write designs directly inside our HTML!).
JavaScript (The Brain): This makes the website interactive. It handles what happens when you click the menu button or submit the form.

⭐ Cool Features in This Website
Mobile Friendly: The website looks great on laptops, tablets, and mobile phones.
Form Check (Validation): If someone forgets to type their name, email, or message, the website highlights the box in red and tells them to fill it.
Success Pop-up: Once the form is filled correctly, a beautiful "Form Submitted Successfully" pop-up box appears on the screen.
Reset Form: After submitting, the form automatically clears itself so a new person can use it.

💻 How to Run This on Your Computer
Running this website is incredibly easy. You don't need to install any servers or special software!
Save the index.html file on your computer (e.g., on your Desktop).
Double-click the index.html file.
It will automatically open in your web browser (Chrome, Edge, or Firefox) and work perfectly!

📚 Simple Code Explanations (For Your Viva/Exams)
1. The Mobile Menu (Hamburger Button)
When you click the menu icon on a phone, JavaScript changes the style of the menu from hidden to visible. When you click it again, it hides it.
2. Form Checking (Validation)
When you click "Send Message", JavaScript steps in:
It checks if the Name is empty: nameInput.value.trim() === ""
It checks if the Email has an @ symbol and a dot (.).
If anything is wrong, it adds a red border. If everything is correct, it shows the Success Pop-up.
