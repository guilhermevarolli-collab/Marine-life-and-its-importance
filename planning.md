# Website Planning Document

**Your Name:** Guilherme Castro Varolli  
**Date Started:** 16/04/2026  
**Topic:** Marine Life and Its Importance  

---

## 1. Foundation

### What is your website about?

My website is about marine life and its importance to the planet. It explains different ocean ecosystems, species, and environmental issues. The goal is to educate people and raise awareness about how the oceans affect life on Earth.

### Who is this website for?

The website is for a general audience, especially people with little knowledge about the ocean. It is designed for students and curious users who want to learn basic and interesting facts about marine life in a simple and visual way.

### What should your website accomplish?

1. Help people understand ocean ecosystems  
2. Raise awareness about environmental problems  
3. Show how people can help protect marine life  
4. Share interesting facts about the ocean  

---

## 2. Site Structure

### What pages will you have?

1. **index.html** - Introduction and general information  
2. **page2.html** - Explore marine life (animals and species)  
3. **page3.html** - Why oceans matter  
4. **page4.html** - Threats to marine life  
5. **page5.html** - How to help + contact form  


### Site map
index.html
├── page2.html
├── page3.html
├── page4.html
└── page5.html


All pages are connected through the navigation bar.


### Navigation plan

- Location: Top of every page  
- Type: Horizontal navigation bar  
- Links:
  - Home  
  - Explore Marine Life  
  - Why Oceans Matter  
  - Threats  
  - Help  

Users know the current page through visual consistency and hover effects.


## 3. Design System

### Color Scheme

- Primary: #0077b6 – Ocean blue  
- Secondary: #023e8a – Deep ocean blue  
- Accent: #00b4d8 – Light blue highlight  
- Background: #f1f5f9 – Light background  
- Text: #0f172a – Dark readable text  

**Why:**  
These colors represent the ocean and create a clean, calm, and consistent theme.

### Typography

- Headings: Segoe UI (bold)  
- Body text: Segoe UI  
- Special text: default system fonts  

**Why:**  
Easy to read and consistent across devices.

---

## 4. Design Principles

### Contrast

Headings are larger and darker. Buttons and links use accent colors to stand out.

### Repetition

Same navigation bar, colors, spacing, and layout across all pages.

### Alignment

Content is centered inside a max-width container. Text is left-aligned.

### Proximity

Related content is grouped into sections, making it easier to read.

---

## 5. Page Layouts

<img width="1152" height="2048" alt="image" src="https://github.com/user-attachments/assets/4ed0b896-0cbd-4e5e-9132-1d4b732c0da7" />


### Page 1 (Desktop)
┌──────────────────────────────────────┐
│ Header + Navigation │
│ (Logo + Menu: Home | Vida | etc) │
├──────────────────────────────────────┤
│ Hero Image + Title │
│ "Marine Life and Their Importance" │
├──────────────────────────────────────┤
│ [Image] Text [Image] │
│ Section about marine life │
├──────────────────────────────────────┤
│ [Image] │
│ List / Fun Facts │
├──────────────────────────────────────┤
│ Footer (links/social/buttons) │
└──────────────────────────────────────┘


---

## 6. Technical Planning

### HTML Elements

- Tables: page2 (animal data)  
- Forms: page5 (contact form)  
- Lists: facts and species lists  
- Semantic HTML: header, nav, main, section, footer  
- Images: used on all pages  
- Special characters: symbols like &copy;  

### CSS Approach

### Flexbox

Used for:
- Navigation bar  
- Image + text sections  
- Facts layout  

### Grid

Used for:
- Page5 grid layout  

### Other techniques

- Media queries for responsiveness  
- Hover effects  
- Box shadows and rounded corners  
- Reusable classes 

---

## 7. Content Planning

### Content needed

- Text: descriptions of marine life  
- Images: ocean animals and environments  
- Data: facts and table content  
- Other: YouTube videos  

### Sources

- Educational websites (NOAA, National Geographic)  
- General knowledge  
- Online images  

Credits will be added in footer or documentation.

---

## 8. Development Plan

### Build order

1. Create HTML structure  
2. Add navigation  
3. Create CSS layout  
4. Add content  
5. Test responsiveness  
6. Fix errors  

### Challenges

#### Challenge 1  
- What: Layout alignment  
- Why: Difficult positioning  
- Plan: Use Flexbox  

#### Challenge 2  
- What: Responsive design  
- Why: Layout breaks on mobile  
- Plan: Use media queries  

#### Challenge 3  
- What: Image sizing  
- Why: Images too large  
- Plan: Adjust CSS sizes  

---

## 9. Tools

- Editor: VS Code  
- Browsers: Chrome, Edge  
- Wireframes: Simple planning  
- Version control: Git + GitHub  
- Validators: W3C  

### Code Generators

No major generators used.  
Code was written manually to better understand HTML and CSS.

---

## 10. Research

### HTML Evolution

HTML started as a simple language for structuring text. Over time, it evolved through versions like HTML4 and HTML5. HTML5 introduced semantic elements like `<nav>`, `<section>`, and `<article>`, which improve structure and accessibility. These elements make websites easier to understand for both developers and browsers.

### CSS Evolution

CSS has improved with features like Flexbox and Grid. Flexbox allows better alignment of elements in one direction, while Grid allows two-dimensional layouts. Responsive design using media queries also became important, allowing websites to work on different screen sizes.

### Why Standards Matter

W3C validation ensures that the website follows web standards. This helps the site work correctly on all browsers and devices, improves accessibility, and makes the code easier to maintain.

## Planning Checklist

(x)Defined purpose and audience  
(x)Planned pages  
(x)Created site map  
(x)Designed navigation  
(x)Chose colors and fonts  
(x)Applied design principles  
(x)Planned layouts  
(x)Planned HTML usage  
(x)Planned CSS approach  
(x)Planned Flexbox  
(x)Planned Grid  
(x)Identified content  
(x)Created plan  
(x)Identified challenges  
(x)Listed tools  
(x)Researched standards  

---

## Final Notes

This project focuses on simplicity, readability, and education. The goal is to make marine life information accessible to everyone.

---

**Planning completed:** 24/04/2026  
**Ready to start coding:** Yes...  
**First step:** Build index.html structure  
