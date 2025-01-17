# stadium-page
football stadium
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ملاعب المحترفين - ولاية بركاء</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004d99;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .content div {
            flex: 1;
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #004d99;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #003366;
        }
    </style>
</head>
<body>
    <header>
        <h1>ملاعب المحترفين - ولاية بركاء</h1>
        <p>متخصص في كرة القدم على الصعيد المحلي</p>
    </header>

    <section>
        <h2>حول ملاعب المحترفين</h2>
        <p>ملاعب المحترفين في ولاية بركاء هي منشأة رياضية متخصصة في كرة القدم، تهدف إلى تقديم بيئة مثالية للاعبين المحليين من مختلف الفرق لتطوير مهاراتهم والمشاركة في المسابقات الرياضية. الملعب يستضيف المسابقات المحلية التي تجمع الفرق الرياضية في السلطنة.</p>

        <div class="content">
            <div>
                <h3>الموقع والمرافق</h3>
                <p>يقع ملعب المحترفين في ولاية بركاء بمحافظة جنوب الباطنة. يوفر الملعب مرافق رياضية متخصصة في كرة القدم، مع أسطح عالية الجودة ومدرجات واسعة للمشجعين. يتمتع الملعب ببنية تحتية حديثة تجعل منه واحدًا من أفضل الملاعب المتخصصة في كرة القدم في السلطنة.</p>
            </div>
            <div>
                <h3>المسابقات المحلية</h3>
                <p>يستضيف ملعب المحترفين في ولاية بركاء المسابقات المحلية التي تضم فرقًا رياضية من مختلف المناطق في السلطنة. توفر هذه المسابقات بيئة تنافسية لتعزيز مهارات اللاعبين المحليين وتمثل فرصة للفرق لاختبار قدراتهم في مباريات حماسية ومثيرة.</p>
            </div>
            <div>
                <h3>التطوير المستقبلي</h3>
                <p>تسعى إدارة ملعب المحترفين إلى تحسين المرافق بشكل مستمر وتوسيع نطاق الأنشطة الرياضية، لتلبية احتياجات الفرق المحلية وتشجيع المزيد من المشاركات في الفعاليات الرياضية. تشمل الخطط المستقبلية تطوير الأسطح الرياضية وزيادة القدرة الاستيعابية للملعب.</p>
            </div>
        </div>

        <h3>تواصل معنا</h3>
        <p>إذا كنت ترغب في الاستفسار أو الحصول على مزيد من المعلومات حول ملعب المحترفين أو المسابقات التي نستضيفها، يمكنك التواصل معنا عبر النموذج التالي.</p>

        <div class="contact-form">
            <form id="contactForm">
                <input type="text" name="name" placeholder="اسمك" required>
                <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
                <textarea name="message" placeholder="رسالتك" rows="4" required></textarea>
                <button type="submit">إرسال</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 ملاعب المحترفين - ولاية بركاء. جميع الحقوق محفوظة.</p>
    </footer>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('شكراً لتواصلك معنا! سنرد عليك في أقرب وقت.');
        });
    </script>
</body>
</html>