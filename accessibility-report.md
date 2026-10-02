# Accessibility Report

## Lighthouse Accessibility Audit

I used the Lighthouse tool in Microsoft Edge DevTools to audit my portfolio website.

### Initial Audit

The first Lighthouse audit produced the following scores:

| Category       | Score |
| -------------- | ----: |
| Performance    |    62 |
| Accessibility  |   100 |
| Best Practices |   100 |
| SEO            |    91 |

The Accessibility score was **100/100**.

The audit also reported a warning that clearing the browser cache timed out. This warning affected the Lighthouse run, but the Accessibility score was still reported as 100.

### Second Audit

I ran Lighthouse again to verify the results.

The second audit produced:

| Category       | Score |
| -------------- | ----: |
| Performance    |    95 |
| Accessibility  |   100 |
| Best Practices |   100 |
| SEO            |    91 |

The Accessibility score remained **100/100**.

## Accessibility Improvements

I applied accessibility practices while building the website, including:

* Adding a `lang="en"` attribute to the HTML document.
* Using semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.
* Adding descriptive `alt` text to the portfolio image.
* Connecting form `<label>` elements to their corresponding form controls using the `for` and `id` attributes.
* Using `<fieldset>` and `<legend>` to group related form controls.
* Marking important form fields as `required`.
* Using `aria-current="page"` to identify the current page in the navigation.
* Using clear heading structures throughout the pages.
* Adding `aria-label="Main navigation"` to the navigation element.

## Before and After Result

The initial Lighthouse audit already gave the website an Accessibility score of **100/100**. After reviewing and verifying the accessibility implementation, the second audit also produced **100/100**.

| Audit              | Accessibility |
| ------------------ | ------------: |
| Initial audit      |   **100/100** |
| Verification audit |   **100/100** |

Because the initial audit already achieved a perfect Accessibility score, there was no numerical increase to record. The second audit confirmed that the accessibility implementation continued to meet Lighthouse's automated accessibility checks.

## Conclusion

The Lighthouse audits showed that my website achieved **100/100 for Accessibility** in both runs. This demonstrates that the accessibility features implemented in the website were successfully recognized by Lighthouse.

The audit also helped me understand the importance of semantic HTML, descriptive alternative text, properly associated form labels, meaningful headings, and accessible navigation.
