---
layout: page
title: Week 3
---

## Wednesday 17 Jan

### 9:00 - start

- Started with adding uploaded furn to frontend
- Understanding frontend working

### 10:00

- Brainstorming the addition of user furnishing request - should be added in layoutplanner
- The layout and furnishing handling

### 12:00

- Fixing: the db is not getting all the data, it is being overwritten somewhere
- Discussing upcoming tasks and course of actions with Ab

## 14:00

- Implemented raw query
- Working on the changeCatalogue and getUserfurnishings
- Handling bugs

### 16:00

- Implemented /furnishing route
- Added user furnishing to repo
- Working on changeCatalogue
- Implemented the redirecting to uploaded after uploading materials

### 18:00

- Debugging: user furnishings are not shown in the 2d
- Problem in code, discussed with Ab about the change
- Modified code of initfurn and planner

### 20:00

- Debugging the top view ref not present
- Problem in ec, furnishing.query
- Fixing bugs in code causing the above problem

### 22:00 - close

---

## Thursday 18 Jan

### 07:00 - start

- The to_json() function was altering the fields leading to the error
- Fixed it by modifying to_json, now query and raw query return the same result

### 09:00

- Started working on adding and showing the currently uploaded furnishing in the uploaded section
- Working on the changeCatalogue to make it work with setGallery

### 10:00

- Met with Ab to discuss the next steps: comment in settings, add uploaded, check status, test layout
- Added comment in lib/settings and moved getCleanFurnishings to /furnishings

### 12:00

- Tested layout and it is working fine now
- Added status key in the incoming furnishings

### 14:00

- Still working on changeCatalogue, not sure where it's going
- Figuring out how to handle type, category, etc.

### 16:00

- Still stuck in changeCatalogue. It's a pain!
- Decided to use a swap variable

### 18:00

- changeCatalogue is working now
- Added current uploaded furnishings to the uploaded section with processing text

### 20:00

- Current uploaded furnishings are shown in the uploaded section
- However, the LayoutPlanner does not have access to the latest furnishings. This is because it doesn't have a shallow copy of the furnishings, it has a deep copy
- Show in 3D: as no slots present in user furnishings, hence causing an error. Slots need material and textures

### 22:00

- Fixing UI and tweaking things

### 22:30 - close

---

## Friday 19 Jan

### 09:00 - start

- Refactoring code and UI
- Need to discuss next steps

### 10:00

- Working on upload model
- Meeting with Ab to work on furnishing textures

### 12:00

- Working on furnishing textures

### 14:00

- Still working on slots
- Able to locate how mesh.materials is being assigned to slots
- Considering shallow copy

### 16:00

- Meeting with Ab to fix slots
- Concluded on slots

### 19:00 - close

---