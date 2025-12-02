- [x] Update assets/css/main.css to set text color to white for .preview-cnt-l .preview-item-val and .preview-cnt-l .preview-blk-title h3
- [x] Test the changes by launching the page in browser and entering data

- [x] Added local storage-based signup/login helpers:
	- file: `assets/js/store-the-data.js` (save, authenticate, current user)
	- Pages wired: `signup.html` and `login.html` (stores user and authenticates)
	- How to test: open `signup.html`, create an account, then open `login.html` and login.
		Check browser DevTools Application -> Local Storage -> resume_users to view stored users.
