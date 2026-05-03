# Lost Pet Finder — Product Requirements Document (Draft)

## 1. Project Summary

**Site Name:** PetAlert

**Audience:** Pet owners of any age in a local area who have just lost a pet — including older adults and people who are not comfortable with technology — as well as local animal shelters that want to list found or unclaimed pets.

**Problem:** When a pet goes missing, there is no quick way to reach the right people nearby — and if the pet has no tag, strangers who find it have no way to contact the owner.

**Goal:** A simple website that lets owners post a missing pet alert, lets neighbors report sightings, and makes it easy to share — designed to be accessible to everyone regardless of tech experience.

---

## 2. Pages and Sections

Posts stay up until the owner removes them or marks the pet as found. When a post is removed or marked as found, all associated messages and data are permanently deleted.

### Main Page — sections top to bottom:

### 2.1 Header
- Clear site title (large, easy to read)
- One-sentence intro explaining what the site does and who it is for
- Navigation bar with quick links to every main section on the page
- Action buttons visible at the top:
  - **"Find Your Pet"** — jumps to the pet card grid with filters so owners can search listings
  - **"Report a Lost Pet"** — jumps to the post form so owners can create a new alert
  - **"How to Help"** — jumps to the how to help a neighbor's lost pet section

### 2.2 Recently Reported Lost Pets
- Search bar at the top so users can type a pet name or description to find a specific listing
- Filter bar below the search bar so users can narrow results by:
  - Animal type (dog, cat, bird, etc.)
  - Date reported
- Cards are sorted by date, with the most recently posted at the top and older posts pushed to the bottom
- A grid of pet cards, each showing:
  - Photo of the pet (icon if no photo uploaded)
  - Pet name and type (dog, cat, etc.)
  - Last seen location and date/time
  - A colored badge showing the search area radius (e.g. "Within 5 km")
- Each card has one button visible to all users:
  - **"Contact Owner"** — opens a new chat thread with the owner in the Chats area (login required)
- If the viewer is the owner of that card, they also see:
  - **"Mark as Reunited"** — moves the post off the main page and marks the pet as found

### 2.3 Post Your Own Missing Pet
- A simple form anyone can fill out (login required to submit):
  - Pet name, type, color, size
  - Last seen address or area
  - Date and time last seen
  - Upload a photo (optional but encouraged)
  - Search radius (small / medium / large area)
- Submit button creates a new card in the section above

### 2.4 What To Do If Your Pet Is Missing
- A checklist with each step written in plain language
- Each step has a small icon next to it to make it easy to scan
- Example steps:
  - [ ] Post on this site right away
  - [ ] Share the post on social media
  - [ ] Check local shelters
  - [ ] Notify your neighbors in person or in a local group chat

### 2.5 How to Help a Neighbor's Lost Pet
- Short tips for people who spot a stray, written in plain language
- What to do:
  - Use the Chats section to contact the owner if you have more details
  - Take a photo if it is safe to do so
  - Note the exact street or landmark where you saw the animal
- What not to do:
  - Do not chase the animal as it may run further away
  - Do not pick up the animal unless it is clearly injured
- What to do if the animal seems hurt:
  - Contact a local shelter or animal control immediately

### 2.6 Tips and How to Use This Site
- A short plain-language guide explaining how the site works for first-time visitors
- Covers:
  - How to search and filter lost pet listings
  - How to post a missing pet report
  - How to contact an owner through Chats
  - How to mark your pet as reunited when found

### 2.7 Chats
- A messaging area only visible to users who have an active lost pet post or who have started a conversation about a listing
- Users can start a chat tied to an existing listing to communicate with the owner
- Only the people involved in that chat can see it — no public group chat
- This is the main way neighbors and owners communicate — no separate per-card DM button

### 2.8 Call to Action (Bottom of Page)
- One big button:
  - **"Report a Lost Pet"** — scrolls back to the form

---

## 3. Features

### Must Have (for class project deadline)
| Feature | Description |
|---|---|
| Pet card grid | Shows lost pet posts with photo, last seen location, and search radius badge |
| Search bar | Type a pet name or description to find a specific listing |
| Filters | Filter cards by animal type and date reported |
| Find Your Pet button | Jumps owners straight to the search and filter grid |
| Mark as Reunited button | Visible only to the owner on their own card — moves the post off the main page |
| Chats area | Dedicated messaging space for users with active posts or existing conversations |
| Post a pet form | Owner fills in details and uploads a photo |
| Simple login | Sign up with name, email, and password — no confirmation email. Required only to post, remove a listing, or use chats. Browse without an account |
| Simple design | Large text, clear buttons, works for people not used to technology |
| Tips and how to use | Plain-language guide explaining how to use every part of the site |

### Nice to Have (stretch goals)
| Feature | Description |
|---|---|
| Sighting report button | Button on each card opens a short form — where you saw the pet, when, and an optional photo — and notifies the owner |
| Shelter uploads | Shelters can post found or unclaimed animals using the same form, with a badge on their card indicating the post is from a shelter |
| Reunited page | Separate page where pets marked as found are displayed, with a running reunited count to show the site's impact |
| Social media search | Site checks for matching posts on Facebook/Nextdoor and links to them |
| Auto-post to social media | Posting on this site also shares to the owner's social media |
| Notifications | Owner gets a site notification and an optional phone push notification when someone reports a sighting — phone notifications only if the owner consents (consent collected in the post form). No email |
| Map view | Shows sighting pins on a map within the search radius |
| Donate button | Opens a list of connected shelters and charities so the user can choose where to send their donation |
| Shelter data access | If a shelter consents, the site can pull their current animal listings and display a small section at the bottom of the main page with the shelter's name, area, and animals in their care |

---

## 4. Design Principles

- **Simple first:** Every button and label must make sense to someone who rarely uses websites — no jargon, no hidden menus
- **Clear buttons:** Every action uses plain descriptive labels (e.g. "Report a Lost Pet", not "Submit") with large tap targets so nothing is hard to press or easy to misread
- **Simple login:** Users sign up with just a name, email, and password — no confirmation emails, no extra steps. Login is only required to post, remove a listing, or use chats. Anyone can browse without an account
- **Not too many features:** The site stays focused — no unnecessary extras that clutter the page or confuse first-time visitors
- **Mobile friendly:** Many people will use this on their phone while out looking for their pet
- **Fast to use:** Owner should be able to post a missing pet in under 2 minutes
- **Local focus:** Posts are filtered to a chosen area so people only see pets missing near them

---

## 5. Out of Scope (not building this for now)

- Complex account management (password reset emails, profile pages, account settings)
- Automatic GPS tracking
- A mobile app

---

## 6. Open Questions

- What area radius options should we offer? (e.g. 1 km, 5 km, 10 km)
- Should sighting reports go straight to the page, or only after the owner approves them?
- How do shelters and charities register to appear on the site? *(not blocking — shelter features are stretch goals)*

---

*Draft version — Grade 7 Class Project*

---

## 7. Lesson 7 MVP Ready Check

**Cards and search**
- [ ] At least one pet card appears on the page with a photo (or placeholder), pet name, type, last seen location, and radius badge
- [ ] Search bar filters cards by pet name or description
- [ ] Animal type filter narrows the card grid correctly
- [ ] Date filter sorts or narrows the card grid correctly
- [ ] "Find Your Pet" button jumps straight to the card grid

**Posting a pet**
- [ ] Post form has all fields: name, type, color, size, last seen location, date and time, photo upload, and radius choice
- [ ] Submitting the form adds a new card to the grid

**Login**
- [ ] Anyone can browse cards without an account
- [ ] Sign up works with just a name, email, and password — no confirmation email
- [ ] Log in and log out work

**Owner controls**
- [ ] "Mark as Reunited" button is visible only to the owner of that card
- [ ] Clicking it removes the card from the main grid

**Chats**
- [ ] "Contact Owner" button appears on every card
- [ ] Clicking it opens a new chat thread with the owner (login required)
- [ ] A logged-in user with an active post can open the Chats area
- [ ] Two users can exchange messages in a chat tied to a listing

**Content and design**
- [ ] "What To Do If Your Pet Is Missing" checklist is on the page
- [ ] "Tips and How to Use This Site" guide is on the page
- [ ] All buttons use plain labels (no technical jargon)
- [ ] Page is readable on a phone screen
