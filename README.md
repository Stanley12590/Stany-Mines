STANY MINES PRO - COMPLETE SYSTEM
================================

Developed by: StanyTz
Year: 2026
Special Thanks: Wolf's and Monster Team

SYSTEM OVERVIEW:
---------------
This is a complete Mines Predictor system with:
1. User App - Main prediction application
2. Admin App - Complete admin dashboard
3. Reseller App - Reseller management panel

FEATURES IMPLEMENTED:
-------------------
✅ 1. FREE TRIALS - 2 times per 24 hours per device
✅ 2. PREMIUM CODES - Auto-expire after duration, one-time use
✅ 3. RESELLER CODES - Resellers get 10+ codes to sell, auto-expire
✅ 4. DEVICE LOCK - Codes work only on first device used
✅ 5. PAYMENT INTEGRATION - HarakaPay API (0712345678 format)
✅ 6. ADMIN DASHBOARD - View all stats, users, payments, codes
✅ 7. WHATSAPP FLOATING - Contact button on all pages
✅ 8. BACK BUTTONS - Navigation on every page
✅ 9. SECURITY - No right click, no code copy (but allow paste)
✅ 10. AUTO-EXPIRE - All codes expire automatically

PAYMENT PACKAGES:
---------------
Week: 3,000 TZS
Month: 4,000 TZS
Lifetime: 5,000 TZS

DATABASE STRUCTURE (Firebase Firestore):
--------------------------------------
Collections:
- users (user data, premium status, free trials)
- premiumCodes (codes, expiry, used status, device lock)
- resellerCodes (reseller codes with limits)
- payments (payment records)
- gameStates (saved game states)
- settings (system settings)

SETUP INSTRUCTIONS:
-----------------
1. Create a new Firebase project
2. Enable Firestore Database
3. Enable Anonymous Authentication
4. Update firebaseConfig in all 3 apps with your Firebase credentials
5. Set HarakaPay API key in user-app.html
6. Set default admin password in admin-app.html
7. Upload all 3 HTML files to web hosting

ADMIN ACCESS:
------------
Default Password: STANY2026
Admin can:
- View all users and their status
- See payment history
- Generate premium/reseller codes
- Set code duration (minutes to lifetime)
- Set limits for resellers
- View statistics and revenue

RESELLER FEATURES:
----------------
- Resellers login with code from admin
- Can generate 10+ codes to sell
- Track which codes are used
- Codes expire based on reseller code duration
- No payment system for resellers (they sell codes manually)

USER FEATURES:
-------------
- Free trials: 2 times per 24 hours
- Premium access via code or payment
- Device lock for codes
- Game state saved automatically
- Can continue playing after browser close
- Responsive design for all devices

SECURITY FEATURES:
----------------
- Codes are one-time use only
- Codes lock to first device used
- No right-click protection
- Code copy protection (but paste allowed in inputs)
- Anonymous user authentication
- Auto-expiry for all codes

NOTES:
-----
1. Phone numbers must start with 07 (Tanzania format)
2. Codes cannot be copied in bulk, only one by one
3. User can clear browser cache but will lose access if free trials used
4. Premium users get direct access without entering code each time
5. All apps use Font Awesome icons
6. Cyberpunk theme with responsive design

CONTACT:
-------
WhatsApp: +255 xxxxxxxxx
Developer: StanyTz
Year: 2026
