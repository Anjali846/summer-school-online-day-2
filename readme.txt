This file describes what CSS types and selectors I used:

1. **Inline CSS:**
   - Applied a background color on the `.card` div: style="background-color: #eaf2f8"

2. **Internal CSS:**
   - Used in the <style> block inside the <head> of index.html.
   - Applied styles to h1, h2, .card, a[href], .bio, and .contact p.

3. **External CSS:**
   - Linked with <link rel="stylesheet" href="style.css"> in index.html.
   - Contains most of the styling including:
     - ID selector: #profile-pic
     - Class selector: .bio, .card
     - Element selectors: h1, p, ul
     - Group selector: h1, h2
     - Descendant selector: .contact p
     - Attribute selector: a[href]
     - Hover effect for links
     - Border and shadow on card
