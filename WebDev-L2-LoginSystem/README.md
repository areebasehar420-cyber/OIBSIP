# Login Authentication System (Web Development Level 2, Task 4)

Front-end only approach (A): HTML, CSS and JavaScript with `localStorage`.

## Features
- Registration with username/email and password
- Password rules: at least 8 characters and at least 1 number
- Duplicate username/email check
- Login with a generic error ("Incorrect username or password") that does not reveal which field is wrong
- Protected dashboard: redirects to login when there is no session
- Logout clears the session and returns to login
- Passwords are hashed (SHA-256 with a random salt per user), never stored as plain text
- Empty-field validation on both forms

## Security note
This is a learning project. Everything is stored in the browser, so it is not suitable for real production use. A real system should hash passwords on the server (for example with bcrypt).

## How to run
Open `index.html` in any browser.

## Screenshots
See the `screenshots/` folder.
