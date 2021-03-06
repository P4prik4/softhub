# Changelog
All notable changes to this project will be documented in this file. This
project adheres to [Semantic Versioning](http://semver.org/).  
Dates are in the following format: [YYYY-MM-DD]

---

# Version 0.2.2 [WIP]
- Changed license from GPL to MIT

# Version 0.2.1 [2017-07-17]

### Major changes

- Removed old `populate` command
- Added `initialize_db`, `fake_data`, `add_reviews` commands (they can be run
  with _manage.py_)
- Added reviews list in user profile
- Added simple update view for users
- Added a sidebar with recommended applications in the ApplicationDetail View  
- (UI) Implemented Card-like design for applications in 'softhub:index' IndexView
- (UI) Using OpenSans font
- (UI) All forms for creation and update views are now inside a nice div

# Version 0.2.0 [2017-04-27]

### Major changes

- Added Categories
- Added Reviews and Ratings
- Added simple user profile page
- Added simple Search
- Added simple demonstrative about page

### Fixes
- Fixed a missing login_required [ff80d45](https://gitlab.com/davcri91/softhub-site/commit/ff80d45450ec7b2c20bf28fa3b9e7539a745da06)

### Documentation
- Added GPLv3 license to the project
- Added instrunctions for using virtualenv

---

# Version 0.1.2 [2017-4-9]

### Major changes
- Work on improving UI
- Handling of Application latest version
- Latest version of the application is the default on Executable Upload View

---

# Version 0.1.1 [2017-03-29]

### Major changes
- Improved softhub/management/commands/populate.py command
- Added Version model
- Initial work on improving UI
- Using Bower for dependencies

---

# Version 0.1.0 [2017-03-21]
Initial version.

Features basic Application, Version and Executable upload views and forms.
