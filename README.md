# FSD-project1
Create a static, desktop-oriented website



Project 1:
Create a static, desktop-oriented website for &quot;The Modern Frame&quot;, a fictional art
gallery. The website should consist of multiple pages and showcase artwork,
exhibitions, artist bios, and contact details — all using only HTML and CSS (no
JavaScript allowed).
Required Pages:
1. Home Page (index.html)
 Welcome message, featured artwork, upcoming exhibition highlight.
2. Gallery Page (gallery.html)
 Display artwork in a structured layout with titles and descriptions.
3. About Page (about.html)
 History of the gallery, list of notable artists, exhibition timeline.
4. Contact Page (contact.html)
 Address, phone, email, and studio hours in a table.
All pages must be linked via a navigation menu in the header.

HTML Overview
1. Structuring an HTML Document:
 Use proper DOCTYPE, &lt;html&gt;, &lt;head&gt;, &lt;body&gt;.
 Include &lt;title&gt;, &lt;meta charset=&quot;UTF-8&quot;&gt;, and semantic tags:
&lt;header&gt;, &lt;nav&gt;, &lt;main&gt;, &lt;section&gt;, &lt;article&gt;, &lt;footer&gt;.

2. Validating and Debugging Your Code:
 Ensure your HTML is valid by using the W3C Markup Validator .
 Use browser developer tools to inspect elements and fix structural
issues.

3. Working with Fonts, Text Blocks, Lists, and Tables:
 Use &lt;h1&gt; to &lt;h6&gt; appropriately for headings.
 Apply &lt;p&gt;, &lt;blockquote&gt;, and &lt;strong&gt;/&lt;em&gt; for formatted text.
 On the About page, create:
 An ordered list of past exhibitions.
 An unordered list of gallery staff.
 On the Contact page, create a table with studio hours (columns: Day,
Opening Time, Closing Time).
4. Using External and Internal Links:
 Link all pages internally using relative paths.
 Add at least one external link (e.g., to a virtual tour on a dummy URL)
with target=&quot;_blank&quot; and rel=&quot;noopener&quot;.

5. Working with Colors, Images, and Multimedia:

 Insert at least 4 images (use placeholder images from
https://picsum.photos/400/300) with proper alt attributes.
 Embed a video (e.g., a gallery tour) using the &lt;video&gt; element with
controls, or use an iframe from a video platform.
 Use named colors, HEX, RGB, and HSL in different parts of the site.

CSS Overview
1. Understanding Cascading Style Sheets:
 Use an external stylesheet (style.css) linked to all pages.
 Apply styles using element, class, ID, and descendant selectors.
2. Working with Margins, Padding, Alignment, and Floating:
 Use margin and padding to create visual breathing space.
 Align text using text-align: center for headings.
 Use float: left/right to wrap text around images (e.g., in the About
section).

3. Understanding the CSS Box Model and Positioning:
 Demonstrate box-sizing: border-box on key elements.
 Use position: static, relative, absolute, and fixed:
 Example: A fixed header that stays at the top.
 An absolutely positioned badge (e.g., &quot;Featured!&quot;) on a hero
image.

4. Using CSS to Do More with Lists, Text, and Navigation:
 Style the navigation menu horizontally using display: inline-block or
float.
 Remove default list styles and apply custom bullets using list-style-
image or list-style: none with pseudo-elements.
 Apply text-transform, letter-spacing, text-decoration, and text-shadow
for visual impact.

5. Creating Layouts Using Modern CSS Techniques:
 Use Flexbox to align the navigation menu and organize content
sections.
 Use CSS Grid to create a gallery layout (e.g., 2×2 grid of artwork on
the Gallery page).
 (Note: Layouts are fixed-width, not responsive. Assume desktop-only
view.)

6. Taking Control of Backgrounds and Borders:
 Apply a background image to the homepage &lt;body&gt; or hero &lt;section&gt;.
 Use background-repeat, background-position, and background-size.
 Add border-radius, border, and box-shadow to image containers and
content boxes.

7. Using CSS Transformations and Transitions:
 Apply transform: scale(1.05) on image hover in the gallery.
 Use transition for smooth color or size changes on buttons and links.
 Example: Navigation links grow slightly and change color on hover.

8. Animating with CSS and the Canvas:
 Create a CSS animation using @keyframes:
 Example: A blinking &quot;Open House!&quot; banner on the homepage.
 Animate opacity, transform, or color over 3 seconds, infinite
loop.

 List of implemented features
 Any known issues
 Browser tested (e.g., Chrome, Firefox)
