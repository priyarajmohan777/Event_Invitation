# Event Invitation Card  
## Date: 08-07-2025  
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


## HTML Code:
```

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Event Invitation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="invite-card">
        <h1>Annual Alumni Meet</h1>
        <h3>Reconnect & Celebrate Together</h3>
        <img src="logo.png" alt="Event Banner">
        <div class="event-details-card">
            <p><strong>Date:</strong> August 25, 2025</p> 
            <p><strong>Time:</strong> 6:00 PM onwards</p> 
            <p><strong>Venue:</strong> College Auditorium</p> 
        </div>
        <footer>
            For RSVP, contact: Priya R<br>
             +91-9876543210 | priya@example.com
        </footer>
    </div>
</body>
</html>
```
## CSS Code:
```
body {
    background-color: #F0F4FF;
    font-family: Arial, Helvetica, sans-serif;
}

.invite-card {
    width: 40%;
    margin: 30px auto;
    padding: 30px;
    background-color: #ffffff;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    text-align: center;
}

h1 {
    color: #6C63FF;
    margin-bottom: 10px;
}

h3 {
    color: #444444;
    margin-bottom: 20px;
}

p {
    font-size: 16px;
    margin-bottom: 10px;
    color: #444444;
}

.event-details-card p strong {
    display: inline;
    text-align: center;
    margin-right: 10px;
    color: #6C63FF;
}

img {
    max-width: 50%;
    border-radius: 15px;
    margin-bottom: 40px;
}

footer {
    font-size: 14px;
    margin-top: 30px;
    padding-top: 15px;
    border-top: 1px solid #ccc;
    color: #444444;
}

```
## Output:
![image](https://github.com/user-attachments/assets/1b2260be-c889-4345-b23d-44ae08028dcc)

## Result:
A responsive and aesthetically pleasing Event Invitation Card was successfully created using separate HTML and CSS files.
