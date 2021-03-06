# myuw-notifications versions

## 1.3.3

### Fixed
- Hiding empty buttons in a notification

## 1.3.2

### Added
- Automatically close the notifications menu when tabbed outside of it

### Fixed
- Access elements within notifications using screen reader

## 1.3.1

### Fixed
- Removing notification from DOM when dismissed from outside of the component

## 1.3.0

### Added
- Keyboard event handling, allow focusing on the next or previous element

### Fixed
- Run `npm audit fix`, fixing some vulnerabilities in node modules

## 1.2.1

### Fixed
- Demo page buttons (get and add notifications) now work properly
- Improved accessibility
  - fixed low contrast when "All caught up"
  - added outline/darker background for buttons when in focus state

## 1.2.0

### Added
- Optional attribute to set a limit on the number of notifications displayed in the list
- Enable scrolling if many notifications
- Delivery pipeline
- Contributing guidelines

## 1.1.0

### Added
- Demo page now includes adding new notifications via a simple form
- Individual notifications are now handled by a child component to more clearly separate functionality and markup/styles, and to simplify DOM manipulation
- Documentation for hooking into notification dismissal event
- Broader support for existing MyUW notification data model (moreInfoButton, confirmButton)
- Parent component (myuw-notifications) keeps track of unique notification IDs

### Fixed
- No duplicate notifications
- Stop observing attributes that can't or won't ever change
- Changed IDs for demo notifications to strings to reflect the expectations of the data model

## 1.0.0

Initial release
