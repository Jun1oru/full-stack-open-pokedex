1. Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

- **Common steps** in **CI** setups are **linting**, **testing**, **building**.
  - Here are some tools for taking care of **linting** in JavaScript / TypeScript: _ESLint, Prettier, StandardJS, JSHint, etc_.
  - For **testing** we can use: _Jest, MochaJS or Playwright, etc_.
  - The **building** tools are varied as well: **Node** for transpiling TypeScript to JavaScript or **Webpack** for building a production version of our codebase.

2. What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

- There are lots of alternatives like: _CircleCI, GitLab CI, JetBrains TeamCity, etc._

3. Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

- It depends on the **size** of the **project**, ours it's a **small to medium** sized one and we can stick to **cloud-based solutions** as **Github Actions**, but if we would've had a **bigger project** we should've used a **self-hosted CI setup**.
