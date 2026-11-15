# Alexander Menshikov

Senior QA Engineer with 10+ years in game QA, functional and localization. I was the sole QA engineer for the launcher platform at MY.GAMES (1B+ registered users), and today I test Overwatch, World of Warcraft, and other Blizzard titles through Terra. Most of my functional work sits where games meet money and accounts: purchases, payments, logins, and the edge cases between them.

This profile is the hands-on side of my CV: you can check how I work without taking my word for it. It holds a test stand I designed and had built with Claude Code, the Python test suites I wrote for it (pytest, Selenium, running in GitHub Actions with a public Allure report), and the manual test documentation the stand is based on.

## Space Shuttle Inc: the test stand

[![CI](https://github.com/alex-menshikov-qa/space-shuttle-qa-stand/actions/workflows/ci.yml/badge.svg)](https://github.com/alex-menshikov-qa/space-shuttle-qa-stand/actions/workflows/ci.yml)
[![Allure report](https://img.shields.io/badge/Allure-report-blue)](https://alex-menshikov-qa.github.io/space-shuttle-qa-stand/)

**[space-shuttle-qa-stand](https://github.com/alex-menshikov-qa/space-shuttle-qa-stand)** · [latest test report](https://alex-menshikov-qa.github.io/space-shuttle-qa-stand/)

Space Shuttle Inc rents out self-flying shuttles and lets customers build their own at the Shipyard. Behind the story is a web app with a REST API and a PostgreSQL database, made to be tested.

- **I designed it.** The requirements come from my manual test documentation, and so do its seeded defects: 41 of the 45 switchable defects reproduce bugs from my own bug reports.
- **Claude Code built it** to those requirements: the app, the database, Docker, and CI. I reviewed every stage before it was merged; the plan and the decisions are in [PLAN.md](https://github.com/alex-menshikov-qa/space-shuttle-qa-stand/blob/main/PLAN.md).
- **The test suites are mine.** 29 UI tests (pytest, Selenium WebDriver, Chrome and Firefox) and 21 API tests (pytest, Requests), running in GitHub Actions on every push, with the Allure report published from `main`.
- **Moved here from my earlier repos** ([stellar-burgers-ui-tests](https://github.com/alex-menshikov-qa/stellar-burgers-ui-tests), [scooter-ui-tests](https://github.com/alex-menshikov-qa/scooter-ui-tests), [scooter-api-tests](https://github.com/alex-menshikov-qa/scooter-api-tests)): new locators, data and URLs for the stand, and a few fixes on the way.

## Manual testing

The test documentation behind the stand lives in my [Notion portfolio](https://testerportfolio.notion.site/Alexander-Menshikov-QA-Engineer-eb649daa45e74833a520fc77237a2fd3): a mind map of the order form, UI and API checklists, a field-validation table, and mobile test cases, along with the bugs they found.

The same portfolio holds my localization QA work: a genre-by-genre guide to writing LQA checklists and sample bug reports.

## Game credits

World of Warcraft: Midnight · Overwatch · Diablo IV: Lord of Hatred · Dispatch · Aliens: Dark Descent · Rogue Legacy 2

## Contact

[LinkedIn](https://www.linkedin.com/in/alexandermenshikov) · menshikovwork@gmail.com
