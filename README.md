# SmartVault — Week 2 Front-End Application

## Project overview
SmartVault is a responsive front-end prototype for organizing personal digital files in one browser-based space. It demonstrates a login screen, dashboard, file categories, saved links, and small web tools.

## Week 2 objectives covered
- Interactive front-end using HTML, CSS, and JavaScript.
- Connected views: sign-in, overview dashboard, file library, media, documents, music, saved links, and mini apps.
- File selection, custom display names, category selection, preview where supported, download, rename, delete, and restore.
- Responsive layouts for desktop and mobile screen sizes.
- Run and testing instructions.

## Main features
1. Demo sign-in with a local browser password.
2. Dashboard with summary counts and quick navigation.
3. My Files — view all active uploaded files.
4. Photos & Videos — browse images and videos separately.
5. Documents — keep PDFs and other document files together.
6. Music — save audio files separately and play supported formats in the browser.
7. Saved Links — save a website name and URL, then open it later.
8. Mini Apps — calculator, notes, to-do list, calendar, photo gallery, and video player.
9. File management — preview supported files, download, rename, move to Recently Deleted, restore, or permanently delete.
10. Responsive interface for desktop and mobile.

## Technologies
- HTML5 — page structure and forms
- CSS3 — layouts, gradients, glass-style panels, and responsive media queries
- Vanilla JavaScript — navigation, forms, file operations, and mini apps
- IndexedDB — local browser storage for uploaded file data
- localStorage/sessionStorage — demo preferences, notes, tasks, and sign-in state

No external JavaScript framework or package installation is required.

## How to run
### Option 1: Open directly
1. Extract the ZIP file.
2. Open the `SmartVault_Updated` folder.
3. Double-click `index.html`.
4. Open it in Google Chrome or Microsoft Edge.

### Option 2: VS Code Live Server
1. Extract the ZIP file.
2. Open VS Code.
3. Select **File → Open Folder** and choose `SmartVault_Updated`.
4. If Live Server is installed, right-click `index.html`.
5. Select **Open with Live Server**.

## How to use
1. First visit: enter a name and create a demo password.
2. Unlock the vault and use the left navigation or dashboard cards.
3. Select **Upload files**, choose one or more files, enter a display name, and choose a category or Auto Detect.
4. Open, download, rename, or delete a file from its card.
5. Deleted files appear under **Recently Deleted** and can be restored or permanently deleted.
6. In **Saved Links**, enter a website name and a complete URL beginning with `https://`, then select Save link.
7. Open a Mini App from its card. Notes and to-do items are saved in the current browser.

## Testing checklist
- [ ] First-time user can create a demo vault.
- [ ] Existing user can unlock with the same browser password.
- [ ] Wrong password is rejected.
- [ ] Dashboard navigation opens each section.
- [ ] Image, video, document, and audio files can be selected and saved.
- [ ] Saved files appear in the appropriate category and My Files.
- [ ] Supported images, videos, PDFs, and audio can be previewed.
- [ ] Download and rename actions work.
- [ ] Delete, restore, and permanent-delete actions work.
- [ ] A valid saved link opens in a new tab.
- [ ] Mini Apps open and their basic interactions work.
- [ ] Layout remains usable on a narrow/mobile screen.

## Important limitations
This is a **front-end demonstration**, not a production cloud-storage service.
- Uploaded files are stored in IndexedDB in the current browser on the current device. They do not automatically sync to another device.
- Clearing browser site data may remove locally stored files. Keep a separate backup of important files.
- The password is a simple local demo lock. It is not secure server-side authentication or encryption. Do not use a real or reused password.
- Saved links open the supplied website; they do not download content from social-media sites.
- Mini apps are browser tools, not installed Android/iOS applications.
- A production version needs a secure backend, authentication, cloud/object storage, database, access controls, and tested backup/recovery.

## Suggested future enhancements
- Backend API and secure authentication
- Cloud file storage and multi-device synchronization
- File size/quota indicators and upload progress
- Search, filters, and sorting
- Stronger accessibility and automated browser testing
- Progressive Web App (PWA) support

## Project status
**Week 2: Front-end prototype.** The current build demonstrates the user interface and browser-side interactions. Backend/cloud functionality is future work.
