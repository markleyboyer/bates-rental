# bates-rental

Rental documents for 932 Bates Church Road — lease agreement and tenant questionnaire.

## Live site
https://markleyboyer.github.io/bates-rental/

## Password
`bates932`

## Deployment
1. Push this repo to GitHub (already created at markleyboyer/bates-rental)
2. Go to repo **Settings → Pages → Source: main branch / root**
3. Site goes live at the URL above in ~1 minute

## Firebase setup note
The app uses Firebase Realtime Database for cross-device sync. Data is stored at:
`bates-rental-default-rtdb.firebaseio.com/bates_rental/tenant_data`

To view or export her answers: Firebase Console → Realtime Database → browse to that path → Export JSON.

## To change the password
Edit line 1 of the `<script>` block in `index.html`:
`const PASSWORD = "bates932";`

## Features
- Password protected
- Two sections: Lease (fill-in-the-blanks) and Questionnaire
- Real-time cross-device sync via Firebase
- Auto-saves as she types
- Print-ready lease view
- Mobile and desktop friendly
