# Daniel Carter — CV Website

A single-page CV website for Daniel Carter, a fictional 27-year-old software developer based in Barcelona. The website presents his professional profile, education, work experience, technical skills and projects in a clear and organized way.

## 1. Project Analysis

### 1.1 User Profile — User Persona

**Name:** Laura Martínez  
**Age:** 32  
**Occupation:** IT Recruiter  
**Location:** Barcelona, Spain  
**Digital skills:** High — uses job platforms, company websites and online CVs daily.

**Background:** Laura works for a technology company and is responsible for finding candidates for web development positions. She usually reviews several CVs in a short period of time, so she needs information that is easy to find and understand.

**Goals:**
- Quickly identify the candidate's profession and level of experience.
- Check technical skills, education and previous jobs.
- See examples of projects to understand the candidate's abilities.
- Find an email address or phone number to contact the candidate.

**Needs and expectations:** Laura expects a professional-looking website with clear headings, short descriptions and organized sections. She often works on a laptop but may also check a candidate's profile on her phone.

**Frustrations:** CV websites with too many visual effects, confusing navigation, very small text or important information that is difficult to find.

**How our website helps:** The CV places Daniel's name and profession at the top. It separates technical information into a sidebar and gives more space to education, experience and projects. The contact details are easy to locate.

### 1.2 Information Architecture

The website is designed as a single-page CV because the main goal is to present Daniel Carter's professional information in a simple and accessible way. Instead of creating different pages, all the content is organized into sections that can be read by scrolling. This allows visitors, especially recruiters, to find the information they need without having to navigate through several menus.

At the top of the page, the header contains Daniel's name, his profession as a software developer and a profile photograph. These are the first elements users see, so they can immediately understand whose CV they are reading and what type of work he does.

Below the header, the information is divided into two columns. The left sidebar includes personal information, skills, languages, certifications and interests. These sections contain short details and lists, so they are suitable for a narrower column. The main column contains the profile summary, education, work experience, selected projects and contact information. These sections need more space because they include explanations, dates and descriptions of previous work.

Each section is placed inside its own box, with a heading that clearly identifies the content. Education, experience and projects are also divided into individual entries. We used this modular organization in Figma, creating separate frames and smaller content groups. It makes the page easier to read and helps us organize the HTML using sections and articles.

On smaller screens, the two columns change into a vertical layout so the content remains readable. Overall, the information architecture focuses on clarity, logical grouping and quick access to the most important information.

### 1.3 Visual Design

For the visual design, we wanted to create a professional CV that looks clean and slightly modern without becoming too complicated. We took inspiration from traditional CV layouts, with a header at the top and two columns below it. This design is appropriate for a software developer because it gives more importance to the information than to decorative elements.

The main colors are dark navy blue, medium blue, white and light gray. The header uses medium blue to highlight Daniel's name and profession, while the left sidebar uses dark navy blue to separate personal details from the main content. The right column has a light background with white content boxes. Dark gray text is used on the white boxes to maintain good readability, and white text is used on the blue backgrounds to create contrast.

We chose Arial, with Helvetica and sans-serif as fallback fonts, because it is simple, familiar and easy to read. Headings are larger and bolder than body text, which creates a clear visual hierarchy. The name is the largest text on the page, followed by the profession and section titles. Dates are displayed next to education, work experience and project names to make the information easier to scan.

Another important decision was to use separate boxes for each section. The boxes have consistent padding, small rounded corners and enough space between them. Thin horizontal lines help distinguish section headings and information groups. The profile photograph is circular with a white border, making the header more personal without distracting from the text.

The desktop layout uses two columns, while the mobile version displays them vertically through a CSS media query. This keeps the design consistent and readable on different screen sizes.

## 2. Figma Design

[View the Daniel Carter CV design in Figma](https://www.figma.com/design/lH2vB1Z7qlbPUWZJMq3txh/Sin-t%C3%ADtulo?node-id=11-2)

## 3. Website Implementation

The project was created with **HTML5 and CSS3**, following the techniques studied in class. No external frameworks were used.

- `index.html` — website content and semantic structure.
- `style.css` — colors, typography, spacing, Flexbox and responsive styles.
- `images/daniel-carter.png` — profile photograph.

The page uses HTML elements such as `header`, `aside`, `main`, `section` and `article`. The visual layout is created with CSS, including the Box Model, Flexbox and media queries.

## 4. How to Run the Website

Open `index.html` in a browser, or open the project folder in Visual Studio Code and use Live Server.

## 5. Live Website

The GitHub Pages link will be added after publishing the website.
      