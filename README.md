
<h2><p dir="rtl">
شرح الدرس </p>
</h2>




* استخدام for loop

<p dir="rtl">
اذا في كود قاعد اكرره عدد من المرات اقدر اختصره</p>


<p dir="rtl">
طريقة كتابة بدون for loop</p>



```swift
print("1 x 10 is \(1 * 10)")
print("2 x 10 is \(2 * 10)")
print("3 x 10 is \(3 * 10)")
print("4 x 10 is \(4 * 10)")
print("5 x 10 is \(5 * 10)")
print("6 x 10 is \(6 * 10)")
print("7 x 10 is \(7 * 10)")
print("8 x 10 is \(8 * 10)")
print("9 x 10 is \(9 * 10)")
print("10 x 10 is \(10 * 10)")
```


<p dir="rtl">
طريقة استخدام for loop</p>



```swift
for i in 1...10 {
    print("\(i) x 10 is \(i * 10)")
}
```



---

<p dir="rtl">
<strong>التمرين</strong> </p>


<p dir="rtl">
السؤال الاول :</p>




1. قم بتعريف المتغير التالي : مصفوفة من الأرقام العشوائية.
2. استخدام for loop والمرور على الارقام وفي كل مرة نتاكد اذا كان العدد زوجي او فردي ونطبعها.
<p dir="rtl">
Hint: 

<p dir="rtl">
لمعرفة العدد اذا كان العدد زوجي او فردي فيجب استخدام if وعمل "باقي القسمة على ٢ " واذا كان الناتج = صفر فهو زوجي ، اما اذا كان الناتج = واحد فهو فردي.</p>




<p dir="rtl">
السؤال الثاني :</p>
<p dir="rtl">
1. 
عرف متغير من نوع عدد صحيح     ->      var total = 0 

<p dir="rtl">
2. 
عرف مصفوفة فيها عدد من الأرقام 

<p dir="rtl">
3. 
اضف for loop تقوم في كل مره بجمع الرقم مع الناتج و طباعة الناتج النهائي
