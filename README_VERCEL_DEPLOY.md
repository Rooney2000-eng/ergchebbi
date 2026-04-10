# Vercel deploy

## Vercel settings
- Root Directory: `./`
- Install Command: `npm install --legacy-peer-deps`
- Build Command: `npm run build`
- Output Directory: `build/client`

## Required environment variables for admin login without a database
```env
ADMIN_EMAIL=soufianechahid30@gmail.com
ADMIN_PASSWORD=admin123
DATABASE_URL=
AUTH_URL=https://your-project-name.vercel.app
AUTH_SECRET=change-this-to-a-long-random-secret
NODE_ENV=production
BOOKING_FROM_EMAIL=onboarding@resend.dev
OWNER_NOTIFICATION_EMAIL=soufianechahid30@gmail.com
RESEND_API_KEY=
```

Important: leave `DATABASE_URL` empty until you have a real PostgreSQL or Neon URL.

## Default admin login
- Email: `soufianechahid30@gmail.com`
- Password: `admin123`
