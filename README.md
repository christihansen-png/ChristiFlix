# ChristiFlix

**A Netflix-style streaming site built with React, with real sign-in through Firebase and real movies from The Movie Database.**

**Live site:** [christi-flix.vercel.app](https://christi-flix.vercel.app)

---

## About

ChristiFlix is a Netflix clone with its own ChristiFlix logo. Visitors create an account and log in before they can browse. The movie rows and trailers come from The Movie Database (TMDB) API, so the movies are always current.

---

## Features

**Accounts**
- Sign up with a name, email and password, or sign in to an existing account
- Accounts are stored with Firebase Authentication, and user info is saved in Firestore
- If you aren't signed in, the site sends you to the login page automatically
- Friendly pop-up error messages (like "wrong password") using React Toastify
- Loading spinner while signing in
- Log out from the profile menu in the nav bar

**Browsing**
- Big hero banner at the top of the home page
- Rows of real movies: Blockbuster Movies, Only on Christiflix, Upcoming and Top Picks for You
- Rows scroll sideways with the mouse wheel
- Nav bar turns dark once you scroll down the page

**Trailer player**
- Click any movie to open its trailer
- Shows the trailer's name, type and release date
- Back arrow returns you to where you were

---

## Built With

- React (Vite)
- React Router (home, login and player pages, movie ID read from the URL)
- Hooks: `useState`, `useEffect`, `useRef`
- Firebase Authentication and Firestore
- TMDB API
- React Toastify
- API token kept in an environment variable, not in the code
- Hosted on Vercel

---

## What I Learned

- Adding real user accounts with Firebase
- Protecting pages so only signed-in users can see them
- Sending a token with an API request in the headers
- Using `useRef` to grab an element and add a scroll listener to it
- Showing a fallback when an API doesn't return what you expect
- Keeping an API token safe with a `.env` file

---

## Author

**Christi Hansen Moore** | Beautiful You Web Studio
[beautifulyouwebstudio.com](https://beautifulyouwebstudio.com) | [Portfolio](https://christihansen-png.github.io/eportfolio.christi/) | [GitHub](https://github.com/christihansen-png)
