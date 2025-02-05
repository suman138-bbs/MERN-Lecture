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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Froms</title>
</head>
<body>
    <form action="">
        Name: <input type="text" required placeholder="Full Name"> <br>
      Password: <input type="password" placeholder="Password"> <br>
      Email: <input type="email" name="" id=""><br>
      DOB: <input type="date" name="" id=""><br>

      Gender: <input type="radio" name="gender" id="">male <input type="radio" name="gender" id="">Female <br>
      Code: <input type="checkbox" name="" id="">HTML<br>
      <input type="checkbox" name="" id="">CSS <br>
      <input type="checkbox" name="" id=""> Tailwind<br>
        <input type="button" value="iNeuron">
      <input type="submit" value="Submit">
      <input type="reset" value="Reset">

     <header>Heading </header>
      <nav></nav>

      <section>
        svjksjkjfbj
      </section>
        
      <li></li>
    </form>
</body>
</html>
cd : change directory

touch example.txt

mkdir

ls : used to show the content of the current directory

pwd : show the full path of current working directory

 ls -la : show all file including hiden file








