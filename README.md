# Event Invitation Card  
## Date: 07-07-2025  
## Objective:

To design a visually appealing event invitation using HTML elements and basic CSS styling for structure and layout.

## Tasks:

#### 1. Set Up the HTML Document:

Use `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, and `<body>` to define the basic structure.

Set the `<title>` as **"Event Invitation"**.

#### ➤ CSS Styling:

- Set background color for the body (e.g., light beige or pastel).
- Apply `font-family` (e.g., `sans-serif`) for consistent typography.

#### 2. Create the Invitation Container:

Wrap the content inside a `<div>` with a class name like `invite-card`.

#### ➤ CSS Styling:

- Define width, padding, border-radius, and a soft `box-shadow`.
- Center the card using `margin: auto` and `margin-top`.

#### 3. Add Event Title and Subtitle:

- Use `<h1>` for the event title (e.g., "Annual Alumni Meet").
- Use `<h3>` for the subtitle (e.g., "Reconnect & Celebrate Together").

#### ➤ CSS Styling:

- Center the headings.
- Apply custom colors and spacing for visual emphasis.

#### 4. Insert Date, Time, and Venue:

- Use `<p>` tags to display:
  - Date: August 25, 2025
  - Time: 6:00 PM onwards
  - Venue: College Auditorium

#### ➤ CSS Styling:

- Use **bold** text for labels (e.g., `Date:`).
- Center or align text with appropriate padding/margin.

#### 5. Add an Image or Banner (Optional):

- Use `<img>` to insert a decorative image or event logo.

#### ➤ CSS Styling:

- Use `max-width: 100%`, `border-radius`, and center alignment.

#### 6. Add RSVP or Contact Info:

- Place inside a `<div>` or `<footer>` section.
- Add contact name, phone number, or RSVP link.

#### ➤ CSS Styling:

- Use smaller `font-size`.
- Add a `border-top` or change background shade for separation.

---

## HTML Code:
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Invitation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="invite-card">
        <h1>Annual Alumni Meet</h1>
        <h3>Reconnect & Celebrate Together</h3>
        <img src="event-banner.jpg" alt="Event Banner">
        <div class="event-details">
            <p><strong>Date:</strong> August 25, 2025</p>
            <p><strong>Time:</strong> 6:00 PM onwards</p>
            <p><strong>Venue:</strong> College Auditorium</p>
        </div>
        <footer>
            For RSVP, contact: Priya R<br>
            📞 +91-9876543210 | 📧 priya@example.com
        </footer>
    </div>
</body>
</html>
```
## CSS Code:
```
body {
    background-color: #f9f4e7;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
}

.invite-card {
    width: 60%;
    margin: 50px auto;
    padding: 30px;
    background-color: #ffffff;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    text-align: center;
}

h1 {
    color: #d2691e;
    margin-bottom: 10px;
}

h3 {
    color: #666666;
    margin-bottom: 20px;
}

p {
    font-size: 16px;
    line-height: 1.6;
}

.event-details p strong {
    display: inline-block;
    width: 70px;
    text-align: right;
    margin-right: 10px;
}

img {
    max-width: 100%;
    border-radius: 10px;
    margin: 20px 0;
}

footer {
    font-size: 14px;
    margin-top: 30px;
    padding-top: 10px;
    border-top: 1px solid #ccc;
    color: #555;
}
```
