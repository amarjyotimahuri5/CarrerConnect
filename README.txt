CareerConnect — Student Job and Internship Portal
=================================================

TECHNOLOGIES
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

HOW TO RUN
1. Extract this ZIP file.
2. Open the CareerConnect folder in Visual Studio Code.
3. Start index.html with the VS Code Live Server extension.
4. The homepage opens first. Visitors can see the website, but selecting a section, job detail, search, or resource asks them to log in or create an account.

REGISTRATION FLOW
1. Account details: name, email, password.
2. Background: choose Student, Recent graduate, or Experienced professional. The form displays different required questions for each choice.
3. Skills and interests: enter skills and the topics/work the user likes.
4. Job preferences: select job fields, work mode, and opportunity type.

The Next button will not continue until all required fields for the current step are completed. Hidden fields for the other profile types are not required.

LOGIN AND RECOMMENDATIONS
- Login is shown when signed out; Logout is shown when signed in.
- Job recommendations are sorted using the profile's selected fields, skills, interests, and work mode.
- Login redirects the user back to the section or job they originally wanted to explore when supported.

IMPORTANT DEMO LIMITATIONS
This is a frontend-only student project. Profiles are stored in the current browser's localStorage, and the password is hashed in the browser where Web Crypto is available. This is NOT production-grade authentication. Do not use real or sensitive personal information. A real deployment needs a secure backend, server-side password hashing, database, validation, HTTPS, and proper session management. Job listings are sample/demo listings and should not be treated as verified vacancies.
