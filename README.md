# living-spaces-code-challenge

# Landing Page Instructions

## Core Requirements
- Create a responsive landing page using only HTML, CSS, and JavaScript/jQuery
- Focus is on layout skills - no functional links required for content elements
- Implement responsive design principles

## Layout Specifications
### Desktop View
- Background colors extend 100% of screen width
- Content container maximum width: 1620px
- Desktop layout maintained until 580px breakpoint

### Mobile View (≤580px)
- Elements stack vertically
- Content layers adapt to mobile format

## Design Elements

### Typography
- Font Family: Arial

### Color Scheme
- Navigation Bar: `#000`
- Main Content: `#2E083D`

### Image Handling
- Images must include responsive class for content area fitting
- Main content images/cards require 6px border radius

## Component Specifications

### Hero Image
- Implement `<picture>` element
- Configure for desktop/mobile versions
- Mobile breakpoint: 580px

### Now Playing Section
- Implementation requires flexbox
- Static content area
- Mobile view: Elements stack vertically at breakpoint


## Tomorrow's Schedule Component

### Data Integration
- Dynamic content population
- Utilize TVmaze API for show listings
- Fetch US schedule for tomorrow's date
- Implement using jQuery `ajax()` method

### Display Requirements
- Create horizontal scrolling UI
- Show first 24 shows from API response

### Optional Enhancement
- Styled gradient scrollbar
- Scrollbar specifications:
  - Base color: `#000` (black bar)
  - Gradient: `#FF5C00` to `#CB2DF`

## Resource References

### Assets & Documentation
- Static Image Assets: [Google Drive Folder](https://drive.google.com/drive/folders/1sH7VPsABdlvINT1b76iHvMUiMBvOMfGk)
- TVmaze API Documentation: [TVmaze API](https://www.tvmaze.com/api)

### Technical Resources
- Flexbox Guide: [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- jQuery Reference: [W3Schools jQuery](https://www.w3schools.com/jquery/)
- jQuery Ajax Tutorial: [W3Schools Ajax](https://www.w3schools.com/jquery/ajax_ajax.asp)
- Horizontal Scrolling Tutorial: [Horizontal Card UI](https://webdesign.tutsplus.com/horizontal-scrolling-card-ui-flexbox-and-css-grid--cms-41922t)
