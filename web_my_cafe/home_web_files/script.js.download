// script.js

// Function to handle form submission
window.submitForm = function() {
    // Get form elements
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    // Validate form data
    if (name.trim() === '' || email.trim() === '' || message.trim() === '') {
        alert('Please fill in all fields');
        return;
    }

    // Display a thank you message
    alert(`Thank you for your message, ${name}!`);

    // Reset the form
    document.getElementById('contactForm').reset();
};