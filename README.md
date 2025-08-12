# Landing Page – My Art Portfolio

This project is the initial design and implementation of my portfolio as an aspiring artist.

## Features
- **Custom Logo**: Uses asset-based logo (`assets/logo-purple.png`) instead of embedded images.
- **Supabase Integration**: 
  - Captures `full_name` and `email` from request invite form.
  - Inserts into `invites` table with `inserted_at` default timestamp.
  - Prevents duplicate sign-ups with friendly duplicate message.
- **Modal System**: 
  - Popups for beta sign-up and team info.
  - Backdrop and close-button interactions.
- **Responsive Design**: Works across desktop and mobile.

## Tech Stack
- **HTML/CSS/JavaScript**
- [Supabase](https://supabase.com/) for database and form submissions.
- Asset management via local `/assets` folder.

