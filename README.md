Rimot Glassy Async Bot - Spam Bot

<div align="center" style="background-color: #000000; padding: 20px; border-radius: 10px;">

<h1 style="color: #00ff00; font-family: 'Courier New', monospace;">🚫 Rimot Glassy Async Bot</h1>
<h3 style="color: #ff0000; font-family: 'Courier New', monospace;">نرم‌افزار اختصاصی - تمام حقوق محفوظ است</h3>

<p style="color: #00ff00; font-size: 16px; font-weight: bold;">
هرگونه کپی، تغییر یا توزیع ممنوع و پیگرد قانونی دارد.
</p>

<p style="color: #ffffff; font-size: 14px;">
سازنده: <a href="https://t.me/Triyed" style="color: #00ff00; text-decoration: none;">[Alireza]</a>
</p>

</div>

📚 راهنمای نصب

<div style="background-color: #000000; padding: 15px; border-radius: 8px; border: 1px solid #00ff00;">

🔧 کتابخانه‌های مورد نیاز

```bash
pip install pyrogram
pip install psutil
pip install pathlib
pip install APScheduler==3.10.0
pip install sqlite3
```

📦 کتابخانه‌های پایتون

```python
# کتابخانه‌های اصلی
from pyrogram.enums import ChatType
from pyrogram import Client, filters, errors
from apscheduler.schedulers.asyncio import AsyncIOScheduler

# کتابخانه‌های استاندارد
import psutil
import sqlite3 
import random
from pathlib import Path
import config
```

⚙️ مراحل نصب

1. نصب کتابخانه‌ها:
   ```bash
   pip install -r requirements.txt
   ```
2. تنظیم فایل config:
   ```python
   # فایل config.py
   admin = "YOUR_ADMIN_ID"
   ```
3. اجرای بات:
   ```bash
   python3 main.py
   ```

🛠 پیش‌نیازها

· Python 3.7+
· API ID و Hash از my.telegram.org
· دسترسی ادمین در بات

⚠️ نکات مهم

<span style="color: #ff0000;">⚠️ هشدار:</span> این بات برای اهداف آموزشی ارائه شده است
<span style="color: #ff0000;">🔒محرمانه:</span> کدها غیرقابل ویرایش و توزیع مجدد هستند

</div>

📞 پشتیبانی

<div style="background-color: #000000; padding: 10px; border-radius: 5px; text-align: center;">
<p style="color: #00ff00;">
برای پشتیبانی با سازنده تماس بگیرید:
<br>
<strong style="color: #ffffff;">Telegram: <a href="https://t.me/Triyed" style="color: #00ff00;">@Triyed</a></strong>
</p>
</div>

---

<div align="center" style="margin-top: 20px;">
<p style="color: #ff0000; font-size: 12px;">
© 2026 Rimot Glassy Async Bot. All Rights Reserved.
<br>
Unauthorized copying, modification, or distribution is strictly prohibited.
</p>
</div>

<style>
body {
    background-color: #000000;
    color: #00ff00;
    font-family: 'Courier New', monospace;
}

code {
    background-color: #1a1a1a;
    color: #00ff00;
    padding: 2px 4px;
    border-radius: 3px;
}

pre {
    background-color: #1a1a1a;
    color: #00ff00;
    padding: 15px;
    border-radius: 5px;
    border: 1px solid #00ff00;
}
</style>
