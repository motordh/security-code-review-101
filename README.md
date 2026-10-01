# Security Code Review 101

OWASP Secure Coding Dojo exercise with a printable completion certificate added on October 1, 2026. Lesson content is unchanged. Modified files: index.html and codeReview101Ctrl.js. Added file: certificate.css.

Source: https://github.com/OWASP/SecureCodingDojo
Source commit: b36286001eee7bfe263ba9209ab6f1da94e34622
Extracted directory: codereview101
License and attribution: see LICENSE and COPYRIGHT.md, plus notices in the source files.

## Upload to GitHub Pages

1. Extract this ZIP on your computer. GitHub does not unpack ZIP uploads.
2. Open https://github.com/motordh/security-code-review-101 and choose Add file > Upload files (or the uploading an existing file link for an empty repository).
3. Upload the extracted files directly to the repository root so index.html is at the top level. Include .nojekyll if your file picker shows it.
4. Commit the files to main.
5. Open Settings > Pages. Under Build and deployment, select Deploy from a branch, main, and /(root), then Save.
6. Wait for GitHub's Pages deployment to finish, then open the URL shown in Settings > Pages.

Expected URL: https://motordh.github.io/security-code-review-101/
Input Validation: https://motordh.github.io/security-code-review-101/#codereview101_inputValidation

## Usage

No compilation, Docker, database, or Dojo training portal is required.
The website loads libraries and styles from cdnjs.cloudflare.com, so internet access to that CDN is required. This is not an offline bundle.
Serve these files using static HTTP/HTTPS hosting; opening index.html directly as a local file may prevent the exercise data loading.

The package includes all six categories of Security Code Review 101. It does not include the full Dojo platform or centralized completion tracking.
For standalone use, omit ?fromPortal. If integrating with an existing Dojo portal that accepts completion codes, retain ?fromPortal before the category fragment.

GitHub Pages publishes the supplied code snippets as static text; the Java, JSP, C++, and other examples are lesson material, not server programs to execute.

## Certificate update for an existing site

Upload and replace index.html and codeReview101Ctrl.js, and add certificate.css at the repository root. The other lesson files do not need replacing.

After completing all 17 questions correctly, select Create certificate, enter the participant name, and choose Print certificate / Save as PDF. The date comes from the participant's device when the course is completed. Use Chrome or Edge, choose landscape if needed, and turn off print headers and footers. Save the PDF and upload it to your Dropbox evidence folder (or save directly to a locally synced Dropbox folder).

Names and completion are not sent to a server. Print before reloading or closing the page: progress and name are only held in the current session. This is a self-reported course completion record, not an independently verified or OWASP-issued certification. Dropbox upload is manual.

Validation: all 17 correct answers were clicked in a local browser; the completion form appeared, the date populated, and printing was disabled until a name was entered. Native print preview was not available in the in-app test browser; verify Save as PDF in Chrome or Edge after uploading.
