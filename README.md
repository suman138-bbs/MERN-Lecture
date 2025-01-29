The `<a>` (anchor) tag in HTML is used to create hyperlinks, allowing users to navigate to different pages, sections within a page, or external resources. The basic syntax looks like this:

```html
<a href="https://example.com">Click here</a>
```

### Key Attributes:
- **`href`**: Specifies the URL the link points to.
- **`target`** (optional): Determines how the link opens.
  - `_self` (default) – Opens in the same tab.
  - `_blank` – Opens in a new tab.
  - `_parent` – Opens in the parent frame.
  - `_top` – Opens in the full body of the window.
- **`rel`** (optional): Defines the relationship between the current page and the linked page (e.g., `nofollow`, `noopener`, `noreferrer`).
- **`download`** (optional): Allows users to download the linked file instead of opening it.

### Examples:

1. **Open in a new tab:**
   ```html
   <a href="https://google.com" target="_blank" rel="noopener noreferrer">Google</a>
   ```

2. **Link to an email:**
   ```html
   <a href="mailto:someone@example.com">Send Email</a>
   ```

3. **Link to a phone number (for mobile users):**
   ```html
   <a href="tel:+1234567890">Call Us</a>
   ```

4. **Download a file:**
   ```html
   <a href="file.pdf" download>Download PDF</a>
   ```

5. **Jump to a section within the same page:**
   ```html
   <a href="#section1">Go to Section 1</a>
   <div id="section1">This is Section 1</div>
   ```

