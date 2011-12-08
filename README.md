# validate.js

validate.js is a lightweight JavaScript form validation library inspired by CodeIgniter.

## How to use inline

    input = document.getElementById('name');
      
    input.addEventListener('blur', function () {
        var errors = document.getElementById("errors");

        validator.validateField(this);
        errors.innerHTML = validator.errors[0] || "";
    });