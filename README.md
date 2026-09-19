## Hi, I'm Eduardo Maytorena

I work in **software quality assurance** and build the applications I test.
I come from the side that breaks systems, and that changes how I write code:
every non-trivial piece leaves a test that covers it, and limitations are
written down instead of discovered in production.

### Projects

**[Vigía](https://github.com/eduardo-mr1/vigia)** · TypeScript
GitHub Action that detects **tests that pass without verifying anything** and
comments it on every Pull Request. A green suite means nothing if the tests
don't assert; this makes that visible at review time. 129 tests of its own,
and it lints itself on every push.

**[Control de Gastos](https://github.com/eduardo-mr1/control-de-gastos)** · React Native + Expo
Expense-tracking app for iOS and Android with offline sync, as a case study
in mobile development and quality.

**[Proyectos de QA](https://github.com/eduardo-mr1/proyectos-de-qa)** · Playwright + Postman
Test plan with 17 designed cases · 18 E2E tests · 25 requests and 96
assertions in Postman · report on 8 real defects with closure verification.

**[Proyectos de Programacion](https://github.com/eduardo-mr1/proyectos-de-programacion)** · Node.js + React
JWT REST API · React client · full-text search engine with an inverted index
and BM25, written with zero dependencies · 56 automated tests, up to 593x
faster than linear search on selective queries.

### The full cycle, on the same application

The last two repositories are connected on purpose. The QA one tests the
application from the other: the E2E suite found the checkbox wasn't
optimistic, exploratory testing uncovered that email was case-sensitive and
locked users out of their own tasks, and every fixed defect left behind a
regression test that keeps it from coming back.

Find the bug, report it with evidence, fix it, verify the fix.

### Tools

`Playwright` `Postman` `Newman` `Jest` `Node.js` `Express` `React`
`React Native` `TypeScript` `SQLite` `Zod` `Git` `GitHub Actions` `Java` `Maven`
