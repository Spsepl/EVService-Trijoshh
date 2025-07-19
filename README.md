# Service Tracker App

A simple web application to track electric vehicle (EV) service requests. The app allows you to add, edit, and delete service requests, and provides dashboard statistics for various request statuses. Built using HTML, Bootstrap, jQuery, and JavaScript.

## Features

- Add new service requests via a modal form.
- View all service requests in a table.
- Edit or delete existing requests.
- Dashboard cards display:
  - Total Service Requests
  - Pending Service Requests
  - In Progress Service Requests
  - Delivered Service Requests

## Technologies Used

- [Bootstrap 4.6.0](https://getbootstrap.com/)
- [jQuery 3.5.1 (Slim)](https://jquery.com/)

## Getting Started

1. **Clone or Download the Repository**

   Save the HTML file, or clone/download the project files to your local machine.

2. **Open in Browser**

   Simply open the `index.html` file in your web browser.

## How to Use

1. **Add Service Request:**
    - Click the `Add Service Request` button.
    - Fill in the customer's details, EV type, ticket number, complaint date, remark, delivery date, amount received, and status.
    - Submit the form to add the request to the list.

2. **View Dashboard:**
    - Cards at the top display counts for each request status.

3. **Edit/Delete Requests:**
    - Use the `Edit` button to modify a request (opens the same modal form pre-filled).
    - Click `Delete` to remove a request.

## File Structure

Assuming a single-file usage:

- `index.html`: Main HTML file containing all markup, style, and scripts.

## Code Overview

- The service request data is stored in a JavaScript array in memory.
- All UI updates (table and dashboard) are dynamic and handled via jQuery.
- No backend or persistent storage; refreshing the page erases all data.

## Customization

- To add more fields or change statuses, edit the modal form and table columns in the HTML.
- To persist data, integrate with a backend/database or use browser storage.

## Example Screenshot

```
[Insert screenshot of the app UI here]
```

## License

This project is for demonstration purposes and has no specific license. Feel free to use and modify as you wish.

---

**Developed with Bootstrap and jQuery**