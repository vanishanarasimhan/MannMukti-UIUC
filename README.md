# MannMukti at Illinois — Website starter

A custom, responsive one-page website built with plain HTML, CSS and JavaScript. No installation or build process is required.

## Open in VS Code

1. Open VS Code and choose **File > Open Folder**, then select `mannmukti-uiuc`.
2. Open `index.html`. If you use the **Live Server** extension, click **Go Live**; otherwise, double-click `index.html` in Finder/File Explorer to preview it in a browser.
3. Edit text in `index.html`, visual styling in `styles.css`, and interactions in `script.js`.

## Things to customize before publishing

Search `index.html` for `[` to find editable placeholders. In particular:

- **Hero**: founding year and group photo. Create an `assets` folder, add `hero.jpg`, and follow the comment above the photo placeholder.
- **Who we are**: add a paragraph specific to the UIUC chapter.
- **Garba**: date, location, event description, and RSVP/ticket link.
- **Gala**: date, location, event description, and RSVP/ticket link.
- **Calendar**: replace `href="#"` with the group's actual calendar URL.
- **Leadership**: replace all names, titles, and portrait placeholders. To use a portrait, replace `<span>PHOTO<br />01</span>` with `<img src="assets/person-name.jpg" alt="Portrait of Person Name">`. Duplicate a `<article class="leader-card">...</article>` block to add more people.
- **Donate**: confirm the approved recipient and add the correct, verified donation URL.
- **Socials**: replace Instagram and GroupMe/Linktree URLs, and update `YOUR-EMAIL@illinois.edu`.

When replacing a placeholder link, **remove the `data-placeholder` attribute** so it becomes clickable. For example:

Before: `<a href="#" data-placeholder="Add the UIUC chapter Instagram link">`

After: `<a href="https://instagram.com/yourchapter" target="_blank" rel="noopener noreferrer">`

For the email link, change `mailto:YOUR-EMAIL@illinois.edu` to the real email and remove `data-placeholder`.

### More photos

To insert an event photo, you can replace the decorative element `<div class="event-graphic ...">...</div>` with an image styled with `width:100%;height:290px;object-fit:cover`, or keep the original poster-like designs.

## Publishing

You can host this site for free using GitHub Pages: commit the three files (and any photos) to a GitHub repository, then enable Pages in repository Settings > Pages, choosing the main branch and root folder.

## Notes

Official national mission/story: https://mannmukti.org/our-story/
UIUC student organization listing: https://one.illinois.edu/mannmukti/home/

The design is independent and is not an official MannMukti brand template. Confirm logo/branding expectations, event details, and donation destination with your chapter before launch.
