# ICT461 Unit 1 Lab - Course Registration Form

## What this is
A one-page course registration form for the ICT461 Unit 1 lab assignment.

## Fields
- Full Name (required)
- Student ID (required)
- Programme (dropdown, required)
- Course (required)

## Run
Open index.html in any browser. No install needed.

## Notes
- Labels are linked to their inputs with `for`/`id`.
- Every field is marked `required` and uses a sensible input type.
- JavaScript checks each field on submit and shows a message under any
  empty field instead of using the browser's default popup.
- This is client-side validation only, for a better user experience.
  A real system would validate the same fields again on the server,
  since anyone can edit or disable the JavaScript in their own browser.
