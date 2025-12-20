# chatAPP

Full-Stack Chat App with Auth & Emails

## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=mongo_uri

NODE_ENV=development

JWT_SECRET=jwt_secret

RESEND_API_KEY=resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=cloudinary_cloud_name
CLOUDINARY_API_KEY=cloudinary_api_key
CLOUDINARY_API_SECRET=cloudinary_api_secret

ARCJET_KEY=arcjet_key
ARCJET_ENV=development
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
