Ecommerce Stripe Redux App
====
![Last Commit](https://img.shields.io/github/last-commit/Siphon880gh/ecommerce-stripe-redux/master)
<a target="_blank" href="https://github.com/Siphon880gh" rel="nofollow"><img src="https://img.shields.io/badge/GitHub--blue?style=social&logo=GitHub" alt="Github" data-canonical-src="https://img.shields.io/badge/GitHub--blue?style=social&logo=GitHub" style="max-width:8.5ch;"></a>
<a target="_blank" href="https://www.linkedin.com/in/weng-fung/" rel="nofollow"><img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue" alt="Linked-In" data-canonical-src="https://img.shields.io/badge/LinkedIn-blue?style=flat&amp;logo=linkedin&amp;labelColor=blue" style="max-width:10ch;"></a>
<a target="_blank" href="https://www.youtube.com/@WayneTeachesCode/" rel="nofollow"><img src="https://img.shields.io/badge/Youtube-red?style=flat&logo=youtube&labelColor=red" alt="Youtube" data-canonical-src="https://img.shields.io/badge/Youtube-red?style=flat&amp;logo=youtube&amp;labelColor=red" style="max-width:10ch;"></a>

Description
---
By Weng Fei Fung. 

This app is an E-Commerce CRA React app with a Shopping Cart integrated with Stripe API. The database is your local  MongoDB. Note mentioning is the global state manager here is Redux which is pretty feature scalable for a huge E-commerce website.

I have closed off the demo to save costs. Here's what you can do depending on your interests:
- If you want to implement Stripe in a CRA React, this could serve partially as your boilerplate.
- If you are NOT using React but want Stripe, refer to my Stripe notes (I like to write coding tutorials) at:
  - Concepts First: https://wengindustry.com/app/bizbrain/?open=Stripe%20-%20_PRIMER
  - Developer: https://wengindustry.com/app/devbrain/?open=Stripe%20Developer%20-%20_PRIMER
  - You may want to test Stripe in Test Mode (separate API key) and using simulation credit card numbers first.
- If you want to use a global state that is more feature scalable than Context API, then you can try Redux. If you look into my git commit history, you can step through how I converted the more simpler Context API to Redux.
  - The conversion is simply a matter of providing a Redux Provider component and passing to it a store that is aware of reducers and initial state. The Redux Provider component's descendant components will be able to dispatch actions and re-render based on new states returned by the reducers. 

Screenshot
---
![Screenshot](docs/e-commerce.gif)

Table of Contents
---
- [Description](#description)
- [Screenshot](#screenshot)
- [Installation](#installation)
- [Questions](#questions)

Installation
---
Run `npm install` to download the necessary node modules. Then run `npm run seed` so the app has products and categories to show. On the app you can sign up for your own account.

Questions
---
- Where can I see more of your repositories?
	- Visit [Siphon880gh's Repositories](https://github.com/Siphon880gh)

- Where can I reach you?
	- You can reach me with additional questions at <a href='mailto:weffung@ucdavis.edu'>weffung@ucdavis.edu</a>.
	- Want to [hire me](//wengindustry.com)?