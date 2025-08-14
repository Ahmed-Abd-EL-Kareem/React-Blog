# Atomic Blog ⚛️

مشروع مدونة تفاعلية مبني بـ React، يوضح استخدام Context API و React Hooks.

## 🚀 الميزات

- **إدارة الحالة**: استخدام React Context API لإدارة حالة المنشورات
- **البحث**: إمكانية البحث في المنشورات حسب العنوان والمحتوى
- **إضافة منشورات**: إضافة منشورات جديدة
- **حذف المنشورات**: إمكانية مسح جميع المنشورات
- **الوضع المظلم**: تبديل بين الوضع الفاتح والمظلم
- **أداء محسن**: استخدام React.memo لتحسين الأداء

## 🛠️ التقنيات المستخدمة

- **React 18** - مكتبة واجهة المستخدم
- **Context API** - لإدارة الحالة
- **React Hooks** - useState, useEffect, useContext, useMemo
- **Faker.js** - لتوليد بيانات وهمية للمنشورات
- **CSS** - للتصميم والتنسيق

## 📁 هيكل المشروع

```
src/
├── App.js          # المكون الرئيسي للتطبيق
├── PostContex.js   # سياق المنشورات وإدارتها
├── Test.js         # مكون اختبار
├── index.js        # نقطة دخول التطبيق
└── style.css       # ملفات التصميم
```

## 🚀 كيفية التشغيل

### المتطلبات الأساسية

- Node.js (الإصدار 14 أو أحدث)
- npm أو yarn

### التثبيت والتشغيل

1. **استنساخ المشروع**

   ```bash
   git clone [رابط المستودع]
   cd atomic-blog
   ```

2. **تثبيت التبعيات**

   ```bash
   npm install
   ```

3. **تشغيل التطبيق في وضع التطوير**

   ```bash
   npm start
   ```

4. **فتح المتصفح**
   - انتقل إلى [http://localhost:3000](http://localhost:3000)

## 📝 كيفية الاستخدام

- **إضافة منشور جديد**: املأ النموذج في أعلى الصفحة
- **البحث**: استخدم حقل البحث للعثور على منشورات محددة
- **تبديل الوضع**: اضغط على زر 🌞/🌛 لتبديل الوضع المظلم
- **مسح المنشورات**: اضغط على زر "Clear posts" لمسح جميع المنشورات

## 🔧 الأوامر المتاحة

```bash
npm start      # تشغيل التطبيق في وضع التطوير
npm test       # تشغيل الاختبارات
npm run build  # بناء التطبيق للإنتاج
npm run eject  # إخراج إعدادات webpack (لا يمكن التراجع عنه)
```

## 📚 ما تم تعلمه

- استخدام React Context API لإدارة الحالة
- تطبيق React.memo لتحسين الأداء
- استخدام Faker.js لتوليد بيانات وهمية
- تنظيم المكونات باستخدام Context Provider
- تطبيق البحث والتصفية على البيانات

## 🤝 المساهمة

نرحب بالمساهمات! يرجى إنشاء issue أو pull request.

## 📄 الترخيص

هذا المشروع مفتوح المصدر ومتاح تحت رخصة MIT.

---

# Atomic Blog ⚛️ (English Version)

An interactive blog project built with React, demonstrating the use of Context API and React Hooks.

## 🚀 Features

- **State Management**: Using React Context API to manage post state
- **Search**: Ability to search posts by title and content
- **Add Posts**: Add new posts
- **Delete Posts**: Clear all posts functionality
- **Dark Mode**: Toggle between light and dark themes
- **Performance**: Using React.memo for performance optimization

## 🛠️ Technologies Used

- **React 18** - UI library
- **Context API** - For state management
- **React Hooks** - useState, useEffect, useContext, useMemo
- **Faker.js** - For generating fake post data
- **CSS** - For styling and design

## 📁 Project Structure

```
src/
├── App.js          # Main application component
├── PostContex.js   # Posts context and management
├── Test.js         # Test component
├── index.js        # Application entry point
└── style.css       # Styling files
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation and Setup

1. **Clone the project**

   ```bash
   git clone [repository-url]
   cd atomic-blog
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the app in development mode**

   ```bash
   npm start
   ```

4. **Open your browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)

## 📝 How to Use

- **Add new post**: Fill out the form at the top of the page
- **Search**: Use the search field to find specific posts
- **Toggle theme**: Click the 🌞/🌛 button to switch dark mode
- **Clear posts**: Click the "Clear posts" button to remove all posts

## 🔧 Available Scripts

```bash
npm start      # Run the app in development mode
npm test       # Run tests
npm run build  # Build the app for production
npm run eject  # Eject webpack config (irreversible)
```

## 📚 What Was Learned

- Using React Context API for state management
- Applying React.memo for performance optimization
- Using Faker.js to generate fake data
- Organizing components with Context Provider
- Implementing search and filtering on data

## 🤝 Contributing

Contributions are welcome! Please create an issue or pull request.

## 📄 License

This project is open source and available under the MIT license.
