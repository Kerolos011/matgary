# Matgary Prototype - متجري

Prototype كامل ثابت HTML/CSS/JavaScript لمنصة SaaS مصرية لإنشاء وإدارة المتاجر الإلكترونية.

## التشغيل محليًا
افتح `index.html` مباشرة في المتصفح، أو شغل سيرفر بسيط:

```bash
python -m http.server 8000
```
ثم افتح:
`http://localhost:8000`

## الصفحات
- `index.html` Landing Page
- `pricing.html` الأسعار
- `create-store.html` إنشاء متجر Wizard
- `dashboard.html` لوحة تحكم التاجر
- `products.html` المنتجات
- `orders.html` الطلبات
- `customers.html` العملاء
- `analytics.html` التقارير
- `settings.html` الإعدادات
- `store.html` واجهة المتجر
- `product.html` صفحة المنتج
- `cart.html` السلة
- `checkout.html` إتمام الطلب
- `restaurant.html` QR Menu للمطاعم
- `admin.html` لوحة إدارة المنصة

## المميزات
- RTL كامل
- Responsive Design
- Mock Data فقط
- LocalStorage للسلة والمنتجات والطلبات
- Chart.js للرسوم البيانية
- جاهز للنشر على Vercel / Netlify / GitHub Pages

## النشر على Vercel
ارفع المجلد إلى GitHub ثم اربطه مع Vercel كـ Static Project.
