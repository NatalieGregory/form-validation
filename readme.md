# Client Side Form Validation

Add client side form validation to Taskly Create, Edit, etc. pages.

## Simple Validtion
1. Submit button should be disabled if fields are blank
1. If any required fields are blanks, prevent the form from posting and
   add an error message to the top of the form.
1. If the form has errors, add and style an error class to append to
   all invalid fields.
1. Disable button when the form submit button is first clicked (to avoid
   the form being submitted twice)
1. Turn date selects into single date picker
1. Add a 'Clear' button to let users start over on the form. It should
   clear all errors & field data and disable the submit button. 
1. Limit task list title to 20 characters
1. Validate when focus is taken off of a field

## Reach Goals

Start on these tasks if you get through all of the others above.

1. Don't duplicate validation logic (how can you submit a form with AJAX and re-render it all with JavaScript)?
2. If a user manually clears the form fields, *without* using the Clear button, the submit button becomes disabled.

