# People's Code

Website for **El Código de la Gente / People's Code**.

Production domain:

https://peoplescode.mx/

## Project structure

The current site is a static website and does not require a build step.

Main files:

- `index.html`
- `styles.css`
- `netlify.toml`
- `assets/`
- `hero-bg.mp4`
- `trailer.mp4`
- `ThePeoplesCode_PressKit.pdf`

## Deployment

The site is intended to be deployed on **Netlify**.

No build command is required for the current version.

The publish directory should be the repository root.

## Netlify Forms

The newsletter/contact form uses **Netlify Forms**.

Form name:

```text
follow

After deploying the repository on Netlify:

Open the Netlify project.
Go to Forms.
Make sure Form detection is enabled.
If form detection was enabled after the initial deployment, trigger a new deploy.
Confirm that the form named follow appears under Active forms.
Form notifications

Submission notifications for the follow form must be configured in the Netlify dashboard.

Go to:

Forms → Submission notifications → Add notification → Email notification

Set the notification email to:

contacto@gantha.mx

This email address is configured in Netlify and is not controlled by the frontend code.

If the site is deployed to a different Netlify project, this notification configuration must be set again in that project.

Hosting outside Netlify

The current form handling relies on Netlify Forms.

If the website is deployed outside Netlify, the follow form will need to be connected to another backend or form-processing service.

Local development

The site can be served locally with any simple static server.

For example:

python3 -m http.server 8080

Then open:

http://localhost:8080
Notes
The site includes responsive behavior for desktop, tablet and mobile.
Mobile uses natural document scrolling instead of the desktop pinned-section behavior.
Background music playback depends on user interaction, as required by browser autoplay policies.
