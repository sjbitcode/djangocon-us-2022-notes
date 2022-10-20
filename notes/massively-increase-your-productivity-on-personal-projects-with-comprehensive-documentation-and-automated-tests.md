## Massively increase your productivity on personal projects with comprehensive documentation and automated tests
### by Simon Willison
---
- lessons from Eventbrite: evolve towards process that works
  - good culture of unittesting and documentation
- our job is not to write software, but to change software
- the perfect commit:
  - **implementation** - code that should change a thing
  - **tests** - prove that implementation works
  - **documentation**
  - link to **issue** thread
- cookiecutter repo templates
  - [python lib](https://github.com/simonw/python-lib), [click](https://github.com/simonw/click-app), [datasette](https://github.com/simonw/datasette-plugin)
  - use GH actions and GH repo templates to set it up
- documentation should live in the same repo
  - get version snapshots of code/documentation updates
  - easier to maintain
  - when docs are far removed, it gets out of date and people don't trust it and don't bother updating them
  - enforce it thru code review
- unittests for documentation
  - extracts heading using regex
- everything needs to link to an issue
  - lots of comments
  - background: reason for change
  - state of play, embed existing code
  - linking to stuff in general, capture all that loose information
  - decisions!!! considered, decide
  - screenshots
  - issue driven development -> don't have to remember anything!
- Release notes (with dates)
- expand definition of "done" to include writing about what you did
  - twitter thread with links/videos/images
  - blog!!
- guilt is the enemy of projects
- avoid side projects with user accounts
  - its not a side project, its an unpaid job
- if you project is tested and documented you have nothing to feel guilty about!

### Talk links from Simon
https://github.com/simonw/djangocon-2022-productivity