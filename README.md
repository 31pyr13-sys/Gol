# # GolHayatCore_Final - اکوسیستم خودپرورش‌دهنده بی‌نهایت

این نسخه از GolHayatCore یک هسته خودپرورش‌دهنده و بینهایت است که:

- داشبورد زنده و گرافیکی دارد
- ماژول‌ها را دانلود، تحلیل و ادغام می‌کند
- رشد و تکامل بی‌نهایت را مدیریت می‌کند

## نصب و اجرای تک خطی در Termux

برای اجرای اکوسیستم با یک دستور کافیست:

```bash
pkg install git python -y && \
git clone https://github.com/31pyr13-sys/Gol.git ~/GolHayatCore_Final && \
cd ~/GolHayatCore_Final && \
pip install -r requirements.txt && \
python gol_hayat_final.py
