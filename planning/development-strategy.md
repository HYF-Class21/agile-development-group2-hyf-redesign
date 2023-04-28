# HYF Redesign

---

## Home Page

## 0. Setup

> Note this is the development strategy for the main page of this website.

- [ ] Boilerplate HTML file
- [ ] empty CSS file
- [ ] CSS file is linked to HTML

---

- This user stories are developed on branch
  [userpersona](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/blob/master/planning/user-personas.md).
- This branch is merged to
  [master](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/tree/master/planning)
  branch after completion.

---

## 1. Title

- This user story is developed on branch `home-title`.
  > **As a user I want to read a title of the page** The site needs a good
  > title/logo at the top left of the page.

### Site Title/logo HTML

- [ ] Header with the web site's title where image of the HYF logo has been
      added.
- [ ] use `header` for the header section
- [ ] use 2 `div` for heder box and for logo box
- [ ] use `a` for link to `Home page`
- [ ] use `img` to add `logo`

### Site Title/logo CSS

- [ ] Title/logo at the top left of the page.
- [ ] use class `header` to style header, display `flex`,
- [ ] use class `header-container` to style header-box, align to the center,
      `flex`
- [ ] use class `logo-container` to style logo, align to the center, `flex`

## 2. Site Navigation

- This user story is developed on branch `home-index-nav`.

  > As a user I need _Nav bar_ that can help me navigate the website quickly.

- [ ] There should be 3 navigation bars with the links to different parts of
      website at top right corner.
- [ ] use `nav`, `a`, `span` for links
- [ ] use `a` for ~a`Apply now` btn.

### Site Navigation HTML

- [ ] Links spread out horizontally with the even distance between them.

### Site Navigation CSS

- [ ] links are presented in grey color,with underline hover effects with color
      blue for first six and 1 with blue color background with white texts. - [
      ] use `header-nav` to style navbars, - [ ] use `nav-links` to style links,
      transform text to uppercase, use no text-decoration, align to the center -
      [ ] use `hover::after` for `nav-links span`, style to make a underline
      hover effects. - [ ] use `nav-button` to style the `Apply now`. Use
      pointer cursor.

## 3. Slogan

- This user story is developed on branch `home-slogan`.
  > As a user I need a slogan and a image.

### HTML

- Should have a heading "HELPING NEW TALENT IN THE TECH WORLD" which should be
  in the middle of the image. then an image by the side of the description.
- Use `section`, `div` tags to introduce slogan part, `h1`for header part.

### CSS

- The image should cover left till right of the page. and slogen should just in
  the middle in 2 lines.
- Use "slogan-section" class to add image to the part.
- Use "slogan-h1 class" for the slogan header.

## 4. Program of the course and an image

- This user story is developed on branch `home-our-program`.
  > As a user I need description of the program and by the end of the
  > description and an image aside of the description. I need to see a link
  > which will lead to another page.

### HTML

Should have a heading "OUR PROGRAM" and paragraph with description of the course
then an image by the side of the description.

- [ ] add `main`, `section`, `div` with `h2` and `p`. Use `a` for btn-link, use
      `img`.

### CSS

Should have blue color with bold pattern for the heading and grey with some blue
coloured letters in the paragraph.

- [ ] use class `our-program` to style the `section`
- [ ] use class `program-container` and style padding, margins, width
- [ ] use class `title-program` to style the **title**
- [ ] use class `program-tex`t to style the text at the **paragraph**
- [ ] use class `btn-program` to style the **button-link**

## 5. Statistic (Our impact)

- This user story is developed on branch `home-statistic`.
  > there should be the datas that shows the impact made to the tech world from
  > the organization.

### Statistic (Our impact) HTML

Should have 3 datas, with title and paragraph.

- [ ] use `section`, `div`, `h1`, `h2` tags for classes

### Statistic(Our impact) CSS

header and descriptions should be written in the blue box which has same size
and same distance with each other.

- [ ] use our-impact-head and oi-para classes to style cheading eading and
      paragraph of statistic part.
- [ ] use cards-heading and cards-para classes to style card heading and
      paragraph respectively.

## 6. Core Values

- This user story is developed on branch `home-core-values`.
  > some informations about the values.

### Core Values HTML

Should have 4 values, each stories contains 1 image and description about the
values.

- [ ] use `section`, `div`, `h3`, `p` tags for classes, and should add image for
      all different values.

### Core Values CSS

4 values should be horizontally and vertically align: means there should be 2
lines and each line should contain 2 values;

## 7. Partners

- This user story is developed on branch `home-partners`.
  > There should be a button with heading "BECOME A PARTNER" at the top right
  > corner align with the heading of the section "Our partners." And should be
  > images of all the partners which are vertically align with each other below
  > the title.

### Partners HTML

should add a button and images of all the partners.

- [ ] Add `section`
- [ ] add `div` for container
- [ ] add extra `div` with `h2` and `a` inside
- [ ] add one more `div` for logo-container
- [ ] use `img` inside `div` to add each logo

### Partners CSS

Design for the button and align the images.

- [ ] use class `partners` to style the `section`
- [ ] use class `partners-container` and style padding, margins, width
- [ ] use class `.title-btn-partners` style Title section
- [ ] use class `title-program` to style the title
- [ ] use class `.btn-program` to style the button-link
- [ ] use style `logos-container` to style the section for logos
- [ ] use style`logo-img` to style logos

## 8. Support

- This user story is developed on branch `home-support`.

> As a user I need to see a clear heading and description of the organization.

- [ ] There should be a clear heading and description of the organization.

### Support HTML

- should be right below the Partners.
- Should have a heading called "Support the developers tomorrow."
- Should have small paragraph with description about the organiztion.
- [ ] Use section and 4 div tags to define the support part of the page.
- [ ] use `support-para-h3` for the header section of the support part.
- [ ] use `p` tag to describe the paragraph.
- [ ] use some `div`tags, label tags ul, li tags and button tag at the end to
      define the button `donate`

### Support CSS

- Heading should be in blue color and paragraph should be in light grey. color.
- [ ] Heading of the support part at the top left corner of the support part
      with same margin from the previous parts.
- [ ] use class `no-of-times` to style the option one time or monthly or select
      your amount.
- [ ] use class `op-1` and `op-rest` to style the options of choices.
- [ ] use class `amt-option` to style the form of the donation.
- [ ] button at the bottom left part 2nd half of the page.

## 9. Contact us

- This user story is developed on branch `home-contact-us`.

> As a user I need to see a clear heading and description of the organization.

- [ ] There should be a clear heading and small description for contact.

### Contact HTML

- should be right below the Contact us.
- Should have small paragraph with description on the left half part while on
  the right half there should be the google map with location triggered.
- Should have a form with the place to write Name, email address and message.

  - [ ] use `section` for this part
  - [ ] use `div` as a container, put in two `div` inside: one - for
        contact-form, second - for the map.
  - [ ] inside the first `div` put `h1` for title and `p` for text. Then use
        `form` with `label`, `input`, `textarea` and `button`
  - [ ] inside the second `div` put `iframe`, indicate `title` and `src`

### Contact CSS

- [ ] the form should be there with coloured blue and the boxes should be there
      to write all the details accordingly.and should have a `send` button.
- [ ] google map should be in the right half of the page. But there should be
      gap between there 2 parts. Vertically left part should be bit smaller than
      right part.

        - [x] use class `contact-section` to style the section

- [ ] use class `contact-container` to style the first `div`
- [ ] use class `contact-form-container` to style the `div` for the form
- [ ] use class `contact-us-form` to style the form
- [ ] use class `support-label` to style labels and `contact-input-text` to
      style the text-box at the form. `support-button` to style the button
- [ ] use classes `maps` and `maps-frame` to style the map

## 10. Footer

- This user story is developed on branch `home-footer`.

> As a user I need _links_ that can help me navigate the website to the
> different social medias.

- [ ] There should be the links of different social medias of the organization
      at the bottom center of the page.

### Footer HTML

- [ ] 4 social media Links with image spread out horizontally with the even
      distance between them.
- Use `section` `div` `h3` `p` and `a` tags to introduce footer to the page.
- `a` tag should be used for the link which will lead to the email of the
  organization. and also whould be used for the logos of all the social media
  with links.

### Footer CSS

- [ ] links are presented with social media logo should align in the bottom
      center of the page.
- use `footer-heading`and `footer-para` classes to style heading and paragraph
  of the footer.
- use `footer-mail` and `footer-smedia` classes to style email and social media
  icons and sm-links to style links.

---

---

## The Program Page

---

## 0. Setup for program page

> Note this is the development strategy for the main page of this website.

- [ ] Boilerplate HTML file
- [ ] empty CSS file
- [ ] CSS file is linked to HTML

---

- This user stories are developed on branch
  [userpersona](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/blob/master/planning/user-personas.md).
- This branch is merged to
  [master](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/tree/master/planning)
  branch after completion.

---

## 1. Title & Navigation Bar for program page

- This user story is developed on branch `program-index`.

> As a user I need _Nav bar_ that can help me navigate the website quickly.

- [ ] There should be 3 navigation bars with the links to different parts of
      website at top right corner.

### Navigation HTML

- [ ] Links spread out horizontally with the even distance between them.
- [ ] use `nav`, `a`, `span` for links
- [ ] use `a` for ~a`Apply now` btn.

### Navigation CSS

- [ ] links are presented in grey color,with underline hover effects with color
      blue for first six and 1 with blue color background with white texts.

      - [ ] use `header-nav` to style navbars,
      - [ ] use `nav-links` to style links, transform text to uppercase, use no text-decoration, align to the center
      - [ ] use `hover::after` for `nav-links span`, style to make a underline hover effects.
      - [ ] use `nav-button` to style the `Apply now`. Use pointer cursor.

## 2. Introduction with extra link, APPLY NOW button and an Image

- This user story is developed on branch `program-introduction`.
  > As a user I need description of the program and by the end of the
  > description i need to see 2 underlined sentences and a button names "APPLY
  > NOW."

### HTML

Should have a heading and a paragraph with description for whom this program
actually is with 2 following underlined sentences and a button which will lead
to the application form.

### CSS

Should have blue color with bold pattern for the heading and grey with some blue
coloured letters in the paragraph button should be in blue background and white
fonts.

## 3. Conditions

- This user story is developed on branch `program-condition`.
  > As a user I need description about who can apply to this program and aside
  > there should be ordered list of the requirement to be eligible to be
  > selected.

### HTML

Should have a heading and a paragraph with description who can apply and the
requirements to be eligible join the course.

### CSS

Should have blue color with bold pattern for the heading and grey paragraph and
at the right side should be the ordered list of the requirements.

## 4. Curriculum info

- This user story is developed on branch `program-curriculum-info`.
  > As a user I need 2 buttons and horrizontally align with eachother at left
  > side and all the languages that are used in the program at the right side.

### HTML

Should have heading, two buttons and images of different languages.

### CSS

2 buttons should horrizontally align with each other, should be just below the
heading part of this section and the images of languages should be vertically
align with the buttons and should be at the right side of the page.

## 5. Footer

- This user story is developed on branch `home-footer`.

> As a user I need _links_ that can help me navigate the website to the
> different social medias.

- [ ] There should be the links of different social medias of the organization
      at the bottom center of the page.

### Footer HTML

- [ ] 4 social media Links with image spread out horizontally with the even
      distance between them.
- Use `section` `div` `h3` `p` and `a` tags to introduce footer to the page.
- `a` tag should be used for the link which will lead to the email of the
  organization. and also whould be used for the logos of all the social media
  with links.

### Footer CSS

- [ ] links are presented with social media logo should align in the bottom
      center of the page.
- use `footer-heading`and `footer-para` classes to style heading and paragraph
  of the footer.
- use `footer-mail` and `footer-smedia` classes to style email and social media
  icons and sm-links to style links.

---

## Support Us page

---

## 0. Setup for support us page

> Note this is the development strategy for the main page of this website.

- [ ] Boilerplate HTML file
- [ ] empty CSS file
- [ ] CSS file is linked to HTML

---

- This user stories are developed on branch
  [userpersona](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/blob/master/planning/user-personas.md).
- This branch is merged to
  [master](https://github.com/HYF-Class21/agile-development-group2-hyf-redesign/tree/master/planning)
  branch after completion.

---

## 1. title & Navigation Bar

- This user story is developed on branch `support-us-index`.
  > As a user I need _Nav bar_ that can help me navigate the website quickly.
- [ ] There should be 3 navigation bars with the links to different parts of
      website at top right corner.

### Site Navigation HTML

- [ ] Links spread out horizontally with the even distance between them.
- [ ] use `nav`, `a`, `span` for links
- [ ] use `a` for ~a`Apply now` btn.

### Site Navigation CSS

- [ ] links are presented in grey color,with underline hover effects with color
      blue for first six and 1 with blue color background with white texts.

        - [ ] use `header-nav` to style navbars,
      - [ ] use `nav-links` to style links, transform text to uppercase, use no text-decoration, align to the center
      - [ ] use `hover::after` for `nav-links span`, style to make a underline hover effects.
      - [ ] use `nav-button` to style the `Apply now`. Use pointer cursor.

## 2. Introduction

- This user story is developed on branch `support-us-introduction`.
  > As a user I need description about why should I become a partner and by the
  > end of the description I need to see 1 nav link to contact the organization.

### HTML

Should have a heading and a paragraph with description which explains why should
I become a partner and a button which will lead to contact the organization by
outlook and one image aside.

- [ ] use `section`, `div`, `h2`, `p`, `a`

### CSS

Should have blue color with bold pattern for the heading and grey with some blue
coloured letters in the paragraph and the button should shade grey while taking
curser in it.

## 3. WHY DONATE?

- This user story is developed on branch `support-us-why-donate`.
  > As a user I need description why we donate.

### HTML

Should have a heading and a paragraph with description why should I donate.

### CSS

Should have blue color with bold pattern for the heading and grey paragraph

## 5. donate form

- This user story is developed on branch `support-us-donate-form`.
  > As a user I need 2 choose buttons and vertically align with eachother at
  > right side and 5 another buttons following with some writing space and
  > another button which is link to confirmation.

### HTML

Should have some text and a button.

### CSS

should have 2 ordered list with some boxes which will turn blue after clicking
on it; writing space and a button at the end.

## 6. Footer

- This user story is developed on branch `support-us-footer`.

> As a user I need _links_ that can help me navigate the website to the
> different social medias.

- [ ] There should be the links of different social medias of the organization
      at the bottom center of the page.

### Footer HTML

- [ ] 4 social media Links with image spread out horizontally with the even
      distance between them.
- Use `section`, `div` ,`h3`, `p` and `a` tags to introduce footer to the page.
- `a` tag should be used for the link which will lead to the email of the
  organization. and also whould be used for the logos of all the social media
  with links.

### Footer CSS

- [ ] 4 social media Links with image spread out horizontally with the even
      distance between them.
- Use `section` `div` `h3` `p` and `a` tags to introduce footer to the page.
- `a` tag should be used for the link which will lead to the email of the
  organization. and also whould be used for the logos of all the social media
  with links.
