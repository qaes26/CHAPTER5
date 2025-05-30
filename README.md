# CHAPTER5
ملخص الفصل الخامس من كتاب نضم المعلومات الاداريه
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شرح الفصل الخامس: إدارة قواعد البيانات</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
            color: #374151; /* Dark gray text */
        }
        .container {
            max-width: 960px; /* Max width for content */
        }
        h1, h2, h3, h4 {
            font-weight: 700; /* Bold headings */
            color: #1f2937; /* Even darker gray for headings */
        }
        .section-card {
            background-color: #ffffff; /* White card background */
            border-radius: 0.75rem; /* Rounded corners */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Subtle shadow */
            padding: 1.5rem; /* Padding inside cards */
            margin-bottom: 1.5rem; /* Space between cards */
        }
        .sub-section-title {
            color: #4b5563; /* Slightly lighter heading for sub-sections */
            font-weight: 600;
            margin-top: 1rem;
            margin-bottom: 0.5rem;
        }
        p {
            line-height: 1.75; /* Improved readability */
            margin-bottom: 1rem;
        }
        ul {
            list-style-type: disc;
            margin-right: 1.5rem;
            margin-bottom: 1rem;
        }
        ul li {
            margin-bottom: 0.5rem;
            line-height: 1.6;
        }
        .author-info {
            font-weight: 600;
            color: #2563eb;
            margin-top: 2rem;
            margin-bottom: 2rem;
            text-align: center;
            font-size: 1.125rem;
        }
        .figure-description {
            background-color: #f0f9ff; /* Very light blue for descriptions */
            border: 1px solid #bfdbfe;
            border-radius: 0.5rem;
            padding: 1rem;
            margin-top: 1rem;
            margin-bottom: 1rem;
            font-style: italic;
            color: #1e40af; /* Darker blue text for description */
        }
    </style>
</head>
<body class="p-4 sm:p-8">
    <div class="container mx-auto">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-blue-700 mb-2">شرح الفصل الخامس: إدارة قواعد البيانات</h1>
            <p class="text-lg text-gray-600">فهم أساسيات تنظيم وإدارة البيانات في نظم المعلومات الإدارية</p>
            <div class="author-info">
                إعداد وتقديم: قيس طلال غالب الجازي
            </div>
        </header>

        <main id="main-content">
            <div class="section-card">
                <h2 class="text-2xl mb-4">مقدمة الفصل (صفحة 133)</h2>
                <p>
                    يبدأ الفصل بتوضيح أن <strong>أهم أهداف أنظمة المعلومات هو تزويد المستخدمين بالمعلومات الدقيقة ذات الصلة في الوقت المناسب</strong>. ويشير إلى أن:
                </p>
                <ul class="list-disc pr-6">
                    <li>
                        <strong>المعلومات الدقيقة:</strong> هي المعلومات الخالية من الأخطاء مثل التكرار وعدم التنسيق.
                    </li>
                    <li>
                        <strong>المعلومات ذات الصلة:</strong> تكون مفيدة لصانعي القرار ولإتمام العمل.
                    </li>
                    <li>
                        <strong>المعلومات في الوقت المناسب:</strong> تتوفر لصانعي القرار عندما يحتاجونها.
                    </li>
                </ul>
                <p>
                    الأنظمة الحديثة تخزن البيانات في ملفات إلكترونية على أجهزة الحواسيب. عندما تحفظ الملفات وتنظم بشكل جيد فإن المستخدمين يستطيعون:
                </p>
                <ul class="list-disc pr-6">
                    <li>تخزين البيانات (Data Saving)</li>
                    <li>الحصول على المعلومات (Query)</li>
                    <li>تعديل البيانات (Data Updating)</li>
                    <li>استرجاع المعلومات (Information Retrieving) بشكل سهل عندما يحتاجون لذلك.</li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">جدول محتويات الفصل (صفحة 134)</h2>
                <p>
                    (هذه الصفحة تحتوي على فهرس لموضوعات الفصل الخامس، وتوضح العناوين الرئيسية والفرعية التي سيتم تناولها في الصفحات التالية).
                </p>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">5.1 تنظيم الملفات (صفحة 135)</h2>
                <p>
                    لتنظيم الملفات وفهم كيفية تخزين البيانات، يجب التعرف على الوحدات الأساسية التي تتكون منها البيانات في الحاسوب:
                </p>
                <h3 class="sub-section-title">البت (Bit):</h3>
                <ul class="list-disc pr-6">
                    <li>هو أصغر وحدة تخزين يمكن للحاسوب تخزينه حيث تكون قيمة (Bit) إما 1 أو صفر.</li>
                    <li>يعتبر اختصار لكلمة (Binary Digit).</li>
                </ul>
                <h3 class="sub-section-title">البايت (Byte):</h3>
                <ul class="list-disc pr-6">
                    <li>هو مجموعة من ثمانية (Bits).</li>
                    <li>يستخدم لتخزين الأرقام ما بين صفر و 255.</li>
                    <li>يمكن تصور (Byte) على الشكل التالي:</li>
                    <div class="figure-description">
                        <strong>جدول يوضح 8 خانات للبتات (تصور البايت):</strong>
                        <p>يُظهر هذا الجدول ثمانية مربعات متجاورة، يمثل كل منها "بت" واحد، ويمكن أن يحتوي على قيمة 0 أو 1. يوضح هذا الترتيب كيف تتجمع البتات لتشكل "بايت" واحد، وهو الوحدة الأساسية لتخزين حرف واحد أو رقم صغير.</p>
                    </div>
                    <li>إن أكبر قيمة يمكن تخزينها في (Byte) هي 11111111 وهي تعادل في النظام العشري 255.</li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="text-2xl mb-4">تابع: تنظيم الملفات (هيكلية البيانات) (صفحة 136)</h2>
                <p>
                    تتدرج وحدات تخزين البيانات في الحاسوب بشكل هرمي تبدأ من أصغر إلى أكبر وحدة على النحو التالي:
                </p>
                <ul class="list-disc pr-6">
                    <li><strong>البت (Bit):</strong> أصغر وحدة.</li>
                    <li><strong>البايت (Byte):</strong> مجموعة من البتات.</li>
                    <li>
                        <strong>الحقل (Field):
