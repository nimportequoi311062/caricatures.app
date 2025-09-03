APP_URL=http://localhost:3000
NODE_ENV=development

DATABASE_URL=postgresql://user:pass@host/db?sslmode=require

S3_ENDPOINT=https://<accountid>.r2.cloudflarestorage.com
S3_REGION=auto
S3_BUCKET=caricatures
S3_ACCESS_KEY_ID=xxxxxxxx
S3_SECRET_ACCESS_KEY=xxxxxxxx

STRIPE_SECRET_KEY=sk_test_xxxxxxxx
STRIPE_WEBHOOK_SECRET=whsec_xxxxxxxx

IMAGE_ENGINE_BASE_URL=https://api.vendor-a.example.com
IMAGE_ENGINE_API_KEY=xxxxxxxx
IMAGE_ENGINE_MODEL_ID=phoenix-1

PRICE_BASE=price_xxxxx
PRICE_WALLPAPER=price_xxxxx
PRICE_SVG=price_xxxxx[page.tsx](https://github.com/user-attachments/files/22121387/page.tsx)
export default function Home(){return (<main><h1>Bienvenue sur Caricatures App</h1></main>)}
