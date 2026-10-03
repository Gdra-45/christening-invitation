[README.txt](https://github.com/user-attachments/files/32999778/README.txt)
CHRISTENING INVITATION - FREE WEBSITE
======================================

FILES
-----
index.html       Main invitation website
baby-photo.jpg   Put the baby's photo here (you add this file)

1. ADD THE BABY PHOTO
----------------------
Put your baby's photo in this same folder and rename it:

baby-photo.jpg

The website will automatically display it.

2. CHANGE THE INVITATION DETAILS
--------------------------------
Open index.html in a text editor and search for the sample details:

Baby Princess
Saturday, November 14, 2026
10:00 AM
Sample Parish Church
Sample Garden Restaurant
Juan & Maria
To be announced

Replace them with your real information.

3. CREATE THE GOOGLE FORM
-------------------------
Create a Google Form for the RSVP. Suggested questions:

- Guest Name
- Will you attend? (Yes / No)
- Number of Guests
- Message (optional)

In Google Forms, open the Responses section and link the responses to a Google Sheet.

4. CONNECT THE GOOGLE FORM
--------------------------
In index.html, find:

href="https://docs.google.com/forms/"

Replace that URL with your actual Google Form link.

Example:
https://docs.google.com/forms/d/e/YOUR-FORM-ID/viewform

5. GOOGLE MAPS
--------------
Find this in index.html:

href="#"

It is the View Location button. Replace # with your Google Maps location link.

6. TEST THE WEBSITE
-------------------
Open index.html on your phone or computer. Test:

- Open Invitation
- RSVP NOW
- Google Form submission
- Google Sheet response
- View Location

7. PUBLISH FREE WITH GITHUB PAGES
----------------------------------
A. Create/sign in to GitHub.
B. Create a new repository, for example:
   christening-invitation
C. Upload index.html and baby-photo.jpg.
D. Open the repository's Settings.
E. Open Pages.
F. Under Build and deployment, choose:
   Deploy from a branch
G. Choose the main branch and / (root), then Save.
H. GitHub will provide your free Pages website address.

The address normally looks similar to:
https://YOUR-USERNAME.github.io/christening-invitation/

You do NOT need to buy a domain.

IMPORTANT
---------
Google Form and Google Sheet creation must be done in your own Google account.
GitHub publishing must be done in your own GitHub account. Keep the Google Sheet
private unless you intentionally want to share it.
