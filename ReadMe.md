

The basic accessibility tips
------
I created an HTML page that shows the basic accessibility tips (https://tanjasav.github.io/UI-Accessibility/) I've learned, such as:

1. Define the natural language of document. Telling the browser which language you are using in your document has many benefits. It’s good for SEO, it helps third-party        translation tools and browsers to identify the right language and dictionary. Defining the correct language in an HTML page helps assistive technology to choose the correct   voice profile or character set.
2. Apply the alt attribute in images. If an image is used as content, apply the alt attribute to describe the images content and function succinctly. When you do that don't    start with „Picture/Image/Graphic of…“, because the screen reader does that anyway.
3. If you need a button, use the `<button>` element and not a `<div>`. Buttons have many benefits/crucial features, for example:
-	focusable;
-	clickable (with mouse and keys);
-	screen readers identify them as buttons.
4. Structure the markup correctly with headings. By creating a sound outline using headings `<h1>` - `<h6>` you are helping users to better understand the structure of page and relationships between individual sections. On top of that, it will help users with assistive technology navigate.
5. Use landmarks to help people navigate site. It is possible and advised to mark up thematic sections with HTML5 `<article>`, `<aside>`, `<nav>`, `<section>`. Sectioning elements are not a replacement for the `<div>` element. Use them to mark up bigger chunks of related content which are distinct from other content. Don't overuse sectioning elements. Use `<div>` for CSS/JS only purposes and sections for semantics.
6. The main page content, header, and footer are also landmarks.
By wrapping the main content of site in a `<main>` element you give some screen users the ability to jump directly to your main content using a shortcut. „The main element represents the main content section of the body of a document or application“ and must not be used more than once per document.
Splitting up content into landmarks is a good thing. `<header>` and `<footer>` behave in all major browsers like landmarks if they are not nested in a `<section>` or `<article>` element.
7. Fieldsets are great for grouping form elements and giving them more context.


Universal design vs inclusive design
 -----
Inclusive design focuses on exploring ways of serving a full spectrum of people who make up a diverse market. This may involve different solutions or processes for different groups of people, rather than a one size fits all approach.
 
In comparison, universal design serves the broadest range of users possible, rather than trying to address individual accessibility or inclusion objectives. Typically, universal design doesn’t provide additional support for ‘edge cases’, instead, providing a single solution that serves the most extensive possible user base, without added accommodations.
 
Additionally, universal design has historically focused on places and architecture and recently been applied to products. Whereas inclusive design can be applied to each of these areas as well as systems and services.
 
The principles of universal design: equitable use, flexibility in use, simple and intuitive use, perceptible information, tolerance for error, low physical effort, size and space for approach and use.
 
Accessibility primarily takes into account making an equivalent experience in physical or digital space for those with disabilities, usually through accommodations like keyboard navigation, curb cuts, captions, and many other methods. For the web, this involves following different standards for accessibility, including keyboard navigation, screen reader accessibility, and more, while user testing these solutions to make sure they provide an equivalent experience for all users.
 
Inclusive design extends solutions to all users who have a broad spectrum of intersectional needs, perspectives, and behaviors, rather than solely creating accommodations for specific disabilities. It focuses on a more holistic group of solutions and processes, taking into account identities, culture, and diverse perspectives in a design process of research and co-design.
 
Considering universal design, inclusive design, and accessibility is key to making products and services that are not only functional, but delightful for all.


Figma file 'Prototype with accessibility support': https://www.figma.com/file/mpCGq4D1fO2l4whAo1yRn7/Prototype-with-accessibility-support?node-id=0%3A1
