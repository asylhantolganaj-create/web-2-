# Assignment #2: Advanced CSS (Flexbox & Grid)

## Student Information
* **Name:** Asylkhan Tolganai
* **Group:** SE-2538

---

## Assignment Parts & Tasks

### Part 1. Flexbox

#### Task 0. Navigation Bar
Created a responsive header using Flexbox with the logo aligned on the left and navigation links on the right.
* `display: flex` applied to the navbar container.
* `justify-content: space-between` and `align-items: center` used for horizontal spacing and vertical alignment.

**Screenshot:**
<img width="1725" height="121" alt="image" src="https://github.com/user-attachments/assets/82af5bbe-8ff7-456b-bad2-74ea7a60644e" />


---

#### Task 1. Card Row
Created a card layout containing three project cards (image, title, description, button).
* Card container structured with Flexbox (`display: flex`).
* Equal card heights ensured via `flex: 1`.
* Added hover animation (`transform: translateY(-3px)`) for smooth user interaction.

**Screenshot:**
<img width="1702" height="582" alt="image" src="https://github.com/user-attachments/assets/053bbbaa-2837-4daf-9a92-a9b858cee2e1" />


---

### Part 2. Grid System

#### Task 2. Page Layout with Grid Areas
Designed the main page layout featuring a Sidebar and Main Content area using CSS Grid.
* Parent container defined with `display: grid`.
* Two-column layout established using `grid-template-columns: 220px 1fr`.

**Screenshot:**
<img width="1292" height="666" alt="image" src="https://github.com/user-attachments/assets/c8df3ab1-7fd8-4f78-88f8-bbd70cb43eeb" />


---

#### Task 3. Image Gallery
Constructed an image gallery with 9 unique photos without duplicates.
* Gallery layout built using `display: grid` and `grid-template-columns: repeat(3, 1fr)`.
* Consistent gaps applied with `gap: 10px`.
* Hover effect implemented using absolute positioning to display a caption overlay on image hover.

**Screenshot:**
<img width="1674" height="147" alt="image" src="https://github.com/user-attachments/assets/bf38bdfb-0c8a-478d-b81e-f1d0bb8b8116" />


---

### Part 3. Combining Flexbox & Grid

#### Task 4. Portfolio Page
Combined both Flexbox and Grid layout systems across the entire page:
* Flexbox used for navigation alignment and individual card content structures.
* CSS Grid used for overall page layout and image gallery positioning.
* Full-width footer styled and aligned at the bottom.


---


During this assignment, I implemented modern CSS layout techniques without using external frameworks or traditional floats. I used Flexbox to manage one-dimensional alignments (such as the navigation bar links and internal card structures) and CSS Grid for two-dimensional structure planning (such as the overall page layout and the 3x3 photo gallery). Hover effects were added to enhance interactive user experience while keeping the visual design clean and aligned.
