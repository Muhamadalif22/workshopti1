# workshopti1

npx create-next-app@latest my-vercel-app
cd my-vercel-app
export default function Home() {
  return (
    <div style={{ textAlign: 'center', marginTop: '50px' }}>
      <h1>🚀 Selamat Datang di Aplikasi Vercel Saya</h1>
      <p>Deploy pertama berhasil!</p>
    </div>
  )
}
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/my-vercel-app.git
git branch -M main
git push -u origin main
