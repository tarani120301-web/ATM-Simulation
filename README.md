# ATM Simulation (Web)

A browser version of my C console ATM program. Built with plain HTML, CSS and JavaScript, with no libraries or build step.

## Features
- Show balance (starts at ₹10,000.00)
- Deposit (amount must be greater than 0)
- Withdraw (amount must be greater than 0 and not more than the balance)
- "Another transaction?" prompt instead of "press 0 to continue"
- Exit with a thank-you screen
- Works on desktop and mobile

## Run locally
Open `index.html` in any browser.

## Host free on GitHub Pages
1. Push `index.html` and `README.md` to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Original logic
The original C program used a `do-while` loop with a `switch` menu. The same logic now lives in `index.html` inside the `menu()`, `showBalance()`, `amountScreen()` and `process()` functions.
