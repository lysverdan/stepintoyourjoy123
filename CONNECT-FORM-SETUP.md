# Connect Page - Form Setup Instructions

## Important: Forms Need Configuration

The Connect page has two forms that Nancy needs to set up with her email service:

### 1. Light Blessings Signup Form
This form needs to connect to Nancy's email marketing service (like MailChimp, ConvertKit, etc.)

**To set up:**
- In `connect.html`, find the Light Blessings form (line ~68)
- Replace `YOUR-EMAIL-SERVICE-URL-HERE` with the actual form submission URL from your email service
- Or embed the email service's provided form code directly

### 2. Contact Form
This form needs to send messages to Nancy's email.

**Options:**
A. Use a form service like:
   - Formspree (https://formspree.io) - Easy, free tier available
   - Netlify Forms (if hosting on Netlify)
   - EmailJS (https://www.emailjs.com)

B. Replace `YOUR-CONTACT-FORM-URL-HERE` with the service's endpoint

**Quick Formspree Setup:**
1. Go to formspree.io
2. Create free account
3. Create a new form
4. Copy the form endpoint URL
5. Replace `YOUR-CONTACT-FORM-URL-HERE` in connect.html with that URL

### Alternative: Simple mailto Link
If Nancy wants a simpler solution temporarily:
Replace the form action with:
```html
<form action="mailto:nancy@stepintoyourjoy.com" method="POST" enctype="text/plain">
```
(But this is less reliable and depends on user's email client)

---

## What's Included in Connect Page:

✅ Light Blessings signup section with benefits list
✅ Contact Nancy section with reason list  
✅ Both forms side-by-side (responsive for mobile)
✅ Nancy's signature closing message
✅ Facebook link in Light Blessings section
✅ Ocean blue theme throughout
✅ Professional form styling with validation

Upload `connect.html` and the updated `styles.css` to see it live!
