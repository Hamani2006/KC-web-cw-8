<p dir="rtl">
<h3><a href="https://github.com/kuwaitcodes/KC-web-cw-8">تمرين </a></h3></p>


<p dir="rtl">
في هذا التمرين راح نقسم درجات الطلاب 🔢!</p>
<h1></h1>
<p dir="rtl">
 <strong>جاااهزييين؟؟؟ 😍</strong></p>

1. قم بعمل fork للـ repository
2. افتح الـ repository باستخدام github desktop
3. افتح ملف script.js وابدأ الحل
4. احذف آخر درجة في مصفوفة grades
5. أضف درجة قيمتها 99 إلى مصفوفة grades
6. اعرض جميع الدرجات في المتغير all_grades_div، باستخدام forEach
 
```
forEach يحب أن تستخدم هذا الكود داخل دالة

all_grades_div.innerHTML += `<div>${element}</div>`;
```

 7. طبق المطلوب أدناه داخل دالة ()search:

<p dir="rtl">
    - عرف متغير باسم filteredGrades واجعل قيمته المطلوب في الأسفل
    
```
     grades.filter((x) => x == inputValue);
``` 

<br>- اطبع المتغير filteredGrades باستخدام ()console.log 


</p>      

8. عرف متغير باسم randomIndex قيمتة دالة ()Math.floor
9. داخل دالة ()Math.floor اكتب التالي:
```
Math.random() * grades.length
```
10. اعرض randomIndex في المتغير random_grade_div 

```
يحب أن تستخدم هذا الكود

random_grade_div.innerHTML = `<div>${grades[randomIndex]}</div>`;
```

11. احفظ اتغيرات وارفع الكود إلى github
12. قم بتسليم التمرين على موقع Coded lab


 <p dir="rtl">
<strong>بونص✨! </strong></p>


 - قم بحل الخطوة 6 باستخدام دالة for loop
 - في دالة ()search إذا لم توجد الدرجة عند البحث، اطبع عن طريق ال ()console.log "الدرجة غير موجوده"



 <p dir="rtl">
 "لا تترددون أنكم تسألون المدرسين 👌"
</p>
