# Qwiklabs Bot

بوت تليجرام لتسجيل الدخول الآلي إلى Google Cloud عبر Qwiklabs labs.

## الميزات
- ✅ تسجيل دخول آلي لـ Google Cloud Console
- ✅ حل CAPTCHA عبر SCTG.xyz
- ✅ قبول Terms of Service تلقائياً
- ✅ نشر على Cloud Run

## التثبيت

```bash
pip install -r requirements.txt
playwright install chromium
cp .env.example .env
python main.py
