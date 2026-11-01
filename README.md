# Vasant Order - APK banane ka tarika

1. github.com par naya repository banao (naam: vasant-order, Public ya Private dono chalega).
2. Is folder ki saari files (hidden `.github` folder samet) us repo mein upload karo.
   Website par "Add file > Upload files" se drag-drop karo. `.github` folder bhi hona chahiye.
3. Repo mein **Actions** tab kholo. Build apne aap shuru ho jayega (3-6 minute).
   Na chale to "Build Android APK" > "Run workflow" dabao.
4. Build hone par us run ko kholo. Neeche **Artifacts** mein `Vasant-Order-APK` milega.
   Download karo, zip kholo, andar `app-debug.apk` hai.
5. APK phone mein bhejo aur install karo (Settings mein "Install unknown apps" allow karna padega).

## Baad mein HTML badalni ho
`www/index.html` ko naye version se replace karke commit karo. APK dobara apne aap ban jayega.

## Dhyan dein
- Yeh debug-signed APK hai. Apne use aur team ko bhejne ke liye theek hai, Play Store ke liye nahi.
- Excel Share aur WhatsApp native tareeke se chalte hain.
- "Print / PDF" button ab PDF banata hai aur seedha Android share sheet kholta hai (jsPDF library build ke time apne aap judti hai).
