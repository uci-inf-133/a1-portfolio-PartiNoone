--Readme document for Tracy Vo, tracymv@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 1/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
    Images with descriptive alt attributes
    Headings and paragraphs
    Multiple pages, with navigation between them
    A footer semantic HTML tag

(b) CSS features
    Padding and margins
    Colors
    Bootstrap image shapes

(c) Advanced features
    Navigation bar
    Nested selectors

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
    I'm passing the W3C validators and AChecker's known/likely problems, but there are many (100+) potential problems listed on AChecker, so I'll group them by WCAG success criteria sections and check numbers.
    1.1 Text alternatives
        Check 178, 8: I tried to be as descriptive as possible in my alt text, and I left out information I thought was not important.
        Check 16: None of my images are decorative, and all of them have alt text.
        Check 3: The images are illustrations, so I have to describe what's in them. I also have to talk about what art style or rendering style I used. I've shortened them as much as I can without excluding info I think is important.
    1.3 Adaptable
        Check 270, 271: I don't switch languages. The only language used is English.
        Check 248: All headers are made in an <ul> element, and the <ul> has the role "menubar" and id "menu".
        Check 250, 262: Generally the page text doesn't reference other items. As for the text accompanying each image, I tried to make it so the page layout made it clear which image each textbox referred to. Many of the text segments are also preceded by a one-word 'title' of some kind that matches the image they describe.
    1.4 Distinguihsable
        Check 14: The point of my portfolio kind of relies on visuals, since it's about art, so some info will inevitably be lost if sight is not used. I do mention a lot in the alt-text.
        Check 251: The text in the art isn't that important in the pieces I chose, except the stickers, which all have their text echoed in the alt-text.
        Check 11: I did not include text that I felt was unimportant in the alt text. The purpose of the images is to show my art, not teach algebra.
    2.4 Navigable
        Check 28: I have a skip to content link in each html file.
        Check 54, 19: All the link text and titles are meaningful/accurate.
        Check 262: See 1.3, Check 250.
        Check 184: All pages are accessible from the header menu, so I think not having a site map in this case is fine.
        Check 42, 43: My headers are used as section titles.
    3.1 Readable
        Check 110: They're compound words, in English. It's readable.
        Check 276: My headers and footers are identical from page to page.
        Check 131: There are no quotes from other sources.

4. How long, in hours, did it take you to complete this assignment?
    21.5 hours
        Thurs: 3-ish hours
        Fri: 2 hours in the morning, 8 hours at night (I stayed up to 4 am)
        Sat: 12-2:30, 3:00pm-6pm, 9am-12pm, 1am-4am

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
    I visited W3Schools pages on HTML, CSS, anSd Bootstrap. I also visited a lot of other websites for more specific things, like help with my footer.
    For HTML and CSS:
        navigation bars (https://www.w3schools.com/css/css_navbar_horizontal.asp)
        centering images (https://www.w3schools.com/css/css3_image_center.asp) and (https://www.w3schools.com/howto/howto_css_image_center.asp)
        position (https://www.w3schools.com/css/css_positioning.asp)
        image cards (https://www.w3schools.com/howto/howto_css_cards.asp)
        subheadings (https://css-tricks.com/html-for-subheadings-and-headings/)
        fade overlay (https://www.w3schools.com/howto/howto_css_image_overlay.asp)
        box shadow (https://www.w3schools.com/cssref/css3_pr_box-shadow.php)
        how to center a column (https://www.tutorialrepublic.com/faq/how-to-center-a-column-in-bootstrap.php)
        transform property (https://www.quackit.com/css/css3/properties/css_transform.cfm)
        accessible navbar (https://dev.to/ilizette/how-to-build-an-accessible-navigation-menu-1omk)
        flip an image (https://www.w3schools.com/howto/howto_css_flip_image.asp)
        background images (https://www.browserstack.com/guide/background-image-syntax-in-html)
    For Bootstrap:
        images (https://www.w3schools.com/bootstrap/bootstrap_ref_css_images.asp)
    Help on my footer:
        Reddit thread (https://www.reddit.com/r/Frontend/comments/k1zj0z/how_to_make_footer_stay_at_bottom_of_page_without/)
        Bootstrap on borders (https://getbootstrap.com/docs/5.3/utilities/borders/)
        5 ways to do footers (https://css-tricks.com/couple-takes-sticky-footer/) 

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
    None


7. Is there anything special we need to know in order to run your code?
    No
