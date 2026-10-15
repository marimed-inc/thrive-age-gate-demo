# Thrive Age Gate Demo

Live demo for the Thrive dispensaries age gate web component.

## Adding to the website

Copy two things from `index.html` (look for the `COPY INTO SITE` comments):

1. **Script** — add this in the site `<head>`:

```html
<script src="https://unpkg.com/@jmeirinkmarimed/age-gate@1.0.38/dist/age-gate.min.js"></script>
```

2. **Component** — add the `<age-gate ...></age-gate>` block near the end of `<body>` (same attributes as in this demo).

If the site does not already load Montserrat, also include the Google Fonts link from `index.html`.

## Demo reset

Use the “Remove age verified” button on the demo page (or clear `localStorage.ageVerified`) to show the gate again after confirming.
