# TESTING.md

The Testing section/document should demonstrate that the site has been thoroughly tested across different areas including validation, responsiveness, browser compatibility, accessibility, and manual and automated testing (depending on the project).

---

## Validators

### HTML
The HTML of all pages was validated using the [W3C Markup Validation Service](https://validator.w3.org/).  
All pages passed without any errors.

### CSS
The CSS files were checked using the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).  
No errors were found in the final version.

### JavaScript (JShint)
All custom JavaScript code was tested using [JShint](https://jshint.com/).  
Output from JShint was reviewed and any issues were resolved or noted.

### Python (PEP8)
Python files were tested using the [CI Python Linter (PEP8)](https://pep8ci.herokuapp.com/).  
Code conforms to PEP8 standards, and any warnings or errors were addressed.

---

## Lighthouse Testing

Google Chrome's Lighthouse tool was used to evaluate:
- Performance
- Accessibility
- Best Practices
- SEO

Screenshots of the Lighthouse results are included below:

*Insert screenshots here*

---

## Accessibility Testing

The site was also tested using [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/).  
All pages were reviewed for contrast errors, missing alt attributes, and ARIA issues. Any issues found were resolved.

Note: Lighthouse also includes accessibility checks, and both tools were used to verify compliance.

---

## Browser Compatibility

The site was tested on the following browsers and versions:

| Browser  | Version  |
|----------|----------|
| Chrome   | XX.X     |
| Firefox  | XX.X     |
| Edge     | XX.X     |
| Brave    | XX.X     |

All pages rendered correctly and behaved as expected across these browsers.

---

## Responsiveness Testing

Responsiveness was tested using:
- Chrome DevTools with preset device views (e.g., iPhone SE, iPhone 12, iPad, Pixel 5, Galaxy S8)
- [Am I Responsive](https://ui.dev/amiresponsive) tool for screenshot and display

All content adjusted appropriately to different screen sizes. No overflow or layout issues were found.

---

## Manual User Testing

Manual testing was conducted to ensure all features functioned as intended.

### Testing Table Example:

| Feature                     | Steps Taken                                      | Expected Result                                | Actual Result     |
|-----------------------------|--------------------------------------------------|------------------------------------------------|-------------------|
| Contact Form Submission     | Fill in all fields and submit                    | Message is sent and confirmation shown         | Pass              |
| Navigation Bar              | Click each link on different screen sizes        | Navigates to correct section or page           | Pass              |
| Form Validation             | Submit empty form                                | Error messages appear                          | Pass              |
| Mobile Navigation           | Test hamburger menu on smaller screen            | Menu opens and links work as expected          | Pass              |

*This table can be expanded with additional features as needed.*

---

## Automated Testing (For Django Projects)

Automated testing was done using Django's built-in testing tools.

- `unittest` was used to test views, forms, and models.
- The `coverage` package was used to check how much of the codebase was tested.

To run the tests:
```bash
python3 manage.py test
```

To check test coverage:
```bash
coverage run --source='.' manage.py test
coverage report
```

*Insert screenshot or attach coverage report here*

---

## Bugs
### Fixed Bugs

- **Issue One**:
    - **Description**: Details of the issue
    - **Fix**: Solution to bug

 - **Issue Two**:
    - **Description**: Details of the issue
    - **Fix**: Solution to bug

### Known Bugs

Can include details of known bugs which have not been resolved here.

All bugs encountered during development that can be fixed, should be. In rare cases unresolved bugs may be accepted, but these would typically be issues outside of the control of the developer.
