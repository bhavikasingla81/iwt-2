# Experiment 24: Responsive HTML/CSS Mini Project

## Aim

Develop and deploy a responsive website using HTML5, CSS3 and Bootstrap CSS, including testing and optimization.

## Run

Open index.html directly in your browser. No JavaScript, Node.js, npm packages or shared tools folder are required. Bootstrap is used only as a local CSS stylesheet.

## Files

- index.html: home page.
- events.html: event cards and weekly schedule.
- join.html: HTML5 registration demonstration.
- confirmation.html: static confirmation page.
- styles.css: project styling and responsive navigation.
- assets/: local SVG illustration and favicon.
- vendor/: Bootstrap CSS and its license; no Bootstrap JavaScript.
- screenshots/: browser output captures and their descriptions.
- .nojekyll: optional static-site marker for GitHub Pages.

## How the HTML/CSS features work

- The mobile menu uses native details/summary elements and CSS media queries. It works with JavaScript disabled and supports keyboard navigation.
- The form uses required, type=email, minlength and maxlength for browser validation. Reset is a native HTML reset button.
- A valid submission opens confirmation.html through the form action. It is a static page, not a database-backed registration result.
- Form controls deliberately omit name attributes so personal field values are not submitted in the URL. No automatic event selection, custom validation script or dynamic success message is used.

## Test manually

1. Open all four pages and follow every navigation link.
2. Resize to phone, tablet and desktop widths. Open and close the Menu details element at phone width.
3. Follow an event's Register interest link, then choose the activity in the form yourself.
4. Submit an empty form and an invalid email to check native HTML5 validation.
5. Enter a name of at least 3 characters, a valid email, an activity and the required confirmation checkbox. Submit: confirmation.html should open.
6. Return to the form, fill fields and press Reset. Native reset clears the form.
7. Test with JavaScript disabled, with Tab/Shift+Tab, and in two available browsers. Check HTML/CSS validation, image alternatives, zoom and mobile overflow.
8. Review local assets and resource sizes in Developer Tools. The illustration is SVG, image dimensions are explicit, and Bootstrap CSS is bundled/minified locally.

## Publish on GitHub Pages (manual)

1. Create a repository in your own GitHub account.
2. Upload index.html, events.html, join.html, confirmation.html, styles.css, assets/, vendor/ and .nojekyll to its root. Do not upload the entire experiment collection.
3. Commit to main. In Settings > Pages, select Deploy from a branch, main, / (root), then save.
4. Open the URL GitHub provides and test every page, asset, native menu and form navigation again.
5. Save your own public-URL screenshots. Deployment has not been performed for you.
