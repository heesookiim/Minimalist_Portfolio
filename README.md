# Personal Website

A portfolio website inspired by Apple products, featuring a dynamic navigation bar and various cutting edge Frontend techniques

[Live Demo](https://spectacular-arrow-048512.framer.app)

## Key Features

- Dynamic Notch Navigation: A smooth and interactive navigation bar inspired by Apple's Dynamic Island.

- Interactive Side Frame: Maintains a rounded edge and accompanying text while scrolling for a seamless experience.

- Responsive Design: Ensures smooth transitions from desktop to tablet to phone mode.

- Framer-Powered Animations: Leveraging Framer's powerful tools for smooth UI interactions.

- 3D Flip Cards: Engaging hover animations in the About section.

- Custom Scroll Animations: Enhances user engagement with fluid section transitions.

- Optimized UI/UX: Improved animations, hover interactions, and content organization.

## Tech Stack

Framework: Framer

Languages: JavaScript, HTML, CSS

Libraries: Framer Motion

Design Principles: Apple-inspired UI, smooth animations, and responsiveness

# Milestones
## 01/25/2025
1. Interactive side frame is completed. In order to keep the rounded edge as well as the text messages while scrolling, the following steps were required:
    1. The side frame components were converted into a separate variant
    2. Set up z-index order (top notch, side frame, and stacks of text in descending order)
    3. Smoothen the interaction using scroll animation


https://github.com/user-attachments/assets/a9597546-f7ad-4c12-8a77-b65962b0910d

2. Updated About section to contain interactive tickets


https://github.com/user-attachments/assets/0aaa7a48-45e5-4cfc-8687-2b24ea0a38eb



## 01/19/2025
Smoothen the notch transition from Tablet to Phone mode. For some reason, the notch was jumping to the middle of the website for one or two frames when shifting the width of the website. I noticed that this was due to the notch for phone was set to fixed instead of relative. Now, the notch smoothly transforms from desktop-tablet-phone.

## 01/18/2025
Fixed interaction for the notch

## 01/14/2025
Created the notch from scartch for customization. 

https://github.com/user-attachments/assets/c1ed63c7-8f59-4537-8a07-ff8d45a37728


## 01/11/2025
Created different versions of notch design (Aiming to fix the top menu bar all the time)
<img width="609" alt="Screenshot 2025-01-11 at 9 42 54 PM" src="https://github.com/user-attachments/assets/27ff18f3-22b0-4e19-af8e-43ba38e0da46" />

## 01/10/2025
- Fixed for better UI/UX:
  - [x] About, Contacts hover animation not resetting properly on mouse out
  - [x] Black line visible when scrolling pages
  - [x] Hamburger icon proportions look misaligned
- updated to have one content per page
![Screenshot 2025-01-10 at 9 41 47 PM](https://github.com/user-attachments/assets/379a4003-76b2-4657-925f-10ce042baef2)

## 01/09/2025
1. In desktop and tablet mode, hamburger menu is clickable. Hovering a cursor will still animate dynamic notch interaction
3. In phone mode, the hamburger menu is clickable, but hovering a cursor is unavailable.

## 01/08/2025
https://github.com/user-attachments/assets/d15ad99c-ecd3-48c2-aadc-dfc052058f20

1. customized navigation bar
2. created link scroll feature to sections

## 01/07/2025
https://github.com/user-attachments/assets/1d9d5f72-f843-47e8-87b5-ad53d9673d3c

Got the idea from the existing [framer components](https://framer.university/resources/dynamic-notch-navigation-component).

Created Apple product like website, which has dynamic island features.

## 01/06/2025
https://github.com/user-attachments/assets/b834f26b-e7c2-4c35-bc9d-f5119d8eef61
1. Added About section for simplicity and better readability
2. Inserted sliding word feature

## 01/05/2025
![Screenshot 2025-01-08 at 10 49 09 AM](https://github.com/user-attachments/assets/e8656b46-6273-491e-83b8-174d3e89b75e)

1. Utilized Framer to create a sample portfolio website. 
2. Added personal features like **Resume** button

### How to create a Dynamic Notch
https://framer.university/resources/dynamic-notch-navigation-component

https://www.youtube.com/watch?v=gVdUWdJu4GE

### How to create a bezel
https://www.youtube.com/watch?v=wxlRb8719lg&t=126s

### How to create 3d flip card
https://framer.university/resources/3d-card-flip-interaction-in-framer

https://www.youtube.com/watch?time_continue=1&v=0GuSvzSw8rI&embeds_referring_euri=https%3A%2F%2Fframer.university%2F&source_ve_path=Mjg2NjY
