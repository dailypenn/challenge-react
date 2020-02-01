# Spring '20 React Challenge

Hey there! Welcome to the DP's web dev challenge~

The goal of this challenge is for you to demonstrate the ability to:

1. Build polished, production grade websites
2. Build products with minimal direction
3. Work within a set timeline

Using React is by no means a requirement for this challenge, you can find starter code for completing this challenge in pure html, jquery, and css [here](https://github.com/dailypenn/s20-challenge). If you're more comfortable completing this challenge using some other frontend library or framework like Angular, Vue, Preact, Elm, Svelte (or one of the thousand other competing frameworks out there) or anything else really, go ahead! We want to judge you at your best, so use whatever tooling you're most comfortable with!

Also, remeber that at DP, we do not judge anyone by his/ her initial performances. Instead, what we value is the progress you made from the moment you received your challenge to the moment your turned in your code. So put efforts into the challenge and good luck.

In this challenge, you'll be building something you may have seen before:
a quiz for [Under the Button](https://www.underthebutton.com/article/2020/01/parents-obligated-talk). We'll be providing you with the quiz's content in a file called `data.json`, but building out the website is completely up to you!

---

### Getting Started
- Make a copy of this repository by either running `git clone https://github.com/dailypenn/s20-challenge-react` on your local computer or simply click on the Green **Clone or download** button and then click on **Download ZIP**.
- Navigate to the cloned repo in the terminal and run `yarn install` or `npm install`
- Run `yarn start` or `npm start`

Note: This project is boostrapped with Create React App (CRA), so hot-reloading has been configured. This means after you run yarn start or npm start, the application will be recompiled automatically after a file is edited. 

---

### General Requirements
- We want you to duplicate the functionality of this [quiz](https://www.underthebutton.com/article/2020/01/parents-obligated-talk). This means showing each question with its options as a form that people can fill out and submit for a response.
- Your code should use `data.json` under `/src` as the content to show in the form.
- Do not **hardcode** anything as we will edit `data.json` and do some simple tests. Any edit to `data.json` takes the following forms: 1) changing the number of questions 2) changing the number of options to each question 3) changing the number of results 4) changing the text of any question, option, or result. You can assume that `data.json` will be well-formatted.
- Your quiz should be functional. The response shown doesn't have to match UTB's actual form, but it should at least be reproducible. Selecting answers and submitting should show one of the responses. Reloading the page and selecting the same answers should show the same response. 

---

### Required Features
- For each question, there should be at most 1 option that is chosen at the same time.
- When the user clicks on **show me my results** button, he/she should not be able to modify the form.
- There should be a **retake quiz** button after the result is shown that allows the user to take the quiz again.
- The user has to give an option to each question before he/she is able to click on **show me my results** button and see the results to the quiz.
- If the majority of responses to the form is A, the first element in `results` should be returned. And if the majority responses is B, the second element in `results` is returned, and so on. Therefore, if you have k options, you should also have k elements in `results`.

---

### Tools
- For styling, use whatever you want:

  - CSS frameworks (Bulma, Bootstrap)
  - CSS files (or SCSS)
  - CSS-in-JS
  - `styled-components`
  - ...

- For state management:

  - Vanilla react state and props
  - Redux
  - ...

- For navigation:
  - React Router
  - ...

---

### Getting Help
If you have any questions about the challenge or need some help, send an email to **Peter Chen** (chen@dailypennsylvanian.com) or **Daniel Tao** (dtao@seas.upenn.edu)

---

### Submission
Either one of the following will work
- Fork this repository and commit your changes to your fork, and submit the **GitHub link** to your fork (please make the repo **public** so we can have access to your code)
- Zip your code and submit the compressed package

Besides your working code, please also take some time to complete `Submissions.txt` so we can have a better understanding of how you feel about the challenge.

All submissions should be emailed to **chen@dailypennsylvanian.com** by Sunday, Feb 2 at 11:59pm.