# Restore the latest edited website

## Goal
Bring back the complete uploaded version so the last colors, text edits, videos, patient post, and existing site features appear again.

## What will be restored
- Use the uploaded `index2.html` content as the homepage shown at `/`, including its latest colors and text.
- Restore the full matching site set and shared styling, scripts, images, galleries, and page links from the uploaded archive.
- Restore the video entries managed through `video2.html` and ensure they appear on the public video gallery and homepage preview.
- Restore the patient post managed through `patient2.html` and ensure it appears on the public patient gallery and homepage preview.
- Restore the editing and save flow included in the archive so future updates do not overwrite or hide existing content.

## Verification
- Check the homepage at desktop and mobile sizes for the restored design and text.
- Open every navigation link and confirm images, videos, patient content, language switching, appointment links, and editing pages load.
- Test the public content endpoints and confirm there are no broken local assets or browser errors.

## Technical details
- Copy only the needed app files from the uploaded archive; no repository metadata will be copied.
- Point the root page to the restored final homepage instead of the older `index.html` snapshot.
- Preserve the uploaded project's existing content identifiers and page-specific storage keys so saved edits map to the correct text and media.
- Keep the public pages indexable while keeping the `*2.html` editing pages excluded from search engines.
