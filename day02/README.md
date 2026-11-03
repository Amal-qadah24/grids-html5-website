# Day 02 – HTML Forms, Tables & Media

**Grids Apps Full Stack Web Development Internship – Foundation Track**

## Overview

Day 02 focuses on HTML5 forms, native validation, tables, media elements, and navigation between multiple web pages.

This project was developed using **HTML5 only**, without CSS or JavaScript.

## Learning Objectives

- Build forms using HTML5 input types.
- Apply native HTML form validation.
- Use labels and fieldsets to organize forms.
- Create semantic HTML tables.
- Embed audio and video using HTML5 media elements.
- Work with relative file paths.
- Build navigation between multiple pages.

## Pages

| File | Description |
|---|---|
| `index.html` | Main homepage and navigation |
| `profile.html` | Academic and professional profile |
| `about.html` | Personal introduction and background |
| `services.html` | Services and comparison table |
| `blog.html` | Blog articles, images, audio, and video |
| `contact.html` | Contact and application form |
| `registration.html` | Challenge H04 – Registration form |

## Project Structure

```text
day02/
│
├── index.html
├── profile.html
├── about.html
├── services.html
├── blog.html
├── contact.html
├── registration.html
├── README.md
│
└── assets/
    ├── images/
    │   ├── img.jpg
    │   └── html5.svg
    │
    └── media/
        ├── learning-audio.mp3
        └── learning-video.mp4
```

## HTML5 Features Used

### Forms & Validation
- `form`, `fieldset`, `legend`
- `label`, `input`, `textarea`, `select`
- Input types: `text`, `email`, `tel`, `password`, `number`, `date`, `radio`, `checkbox`
- Validation attributes: `required`, `minlength`, `maxlength`, `min`, `max`, `pattern`

### Tables
- `table`, `caption`
- `thead`, `tbody`, `tfoot`
- `tr`, `th`, `td`
- `colspan`

### Media
- `img`, `figure`, `figcaption`
- `audio`, `video`, `source`

### Semantic Elements
- `header`, `nav`, `main`
- `section`, `article`, `aside`
- `footer`, `time`, `details`, `summary`

## Challenges

**H04 – Registration Form**

Created a registration form containing personal information, account details, gender selection, interests, country selection, and terms acceptance.

## Notes

- All pages are connected through navigation links.
- Native browser validation is used for form inputs.
- Audio and video require valid media files in `assets/media/`.
- Images must be placed in `assets/images/`.
- Forms currently demonstrate HTML structure and client-side validation; no backend or database submission is implemented.
- Password confirmation matching requires JavaScript or backend validation and is not handled by HTML alone.
- `style.css` is not used in this HTML-only version.

## Exit Ticket

1. **What did I build today?**  
   A multi-page HTML5 website with forms, tables, navigation, and media elements.

2. **What bug or difficulty did I solve?**  
   Working with relative paths and connecting multiple HTML pages.

3. **What concept can I explain clearly?**  
   HTML5 forms, input types, and native form validation.

4. **What remains incomplete?**  
   Backend integration and actual form submission.

---

**Training Track:** Full Stack Web Development  
**Day:** 02  
**Focus:** HTML5 Forms, Tables, Media & Navigation