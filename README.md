
<div dir="rtl">
 
     
# بداية المشروع النهائي 🥳
- الواجب راح يكون بسيط و خفيف و راح يكون بدايه مشروعكم النهائي
-  راح اتحطون فكرتكم و تصميمكم (wireframe) **in Action** 🥁
### خطوات 
1. قم بعمل Repository للمشروع النهائي
2. اسم **Repository**  سيكون اسم المشروع بالانجليزي
3. قم بعملة   Clone وحفظ الملف
4. قم بفتح مشروع xcode جديد و حفظه في clone folder
5. قم بتسميه المشروع في  xcode على اسم مشروع

## iOS✨

1. قم بعمل **Launch Screen** و تتكون من لوقو البرنامج
2. قم بوضع ايقونه البرنامج **App icon**
فيديو للتوضح [هنا](https://www.youtube.com/watch?v=6kD1IZfGsWQ) 
3. قم بتجهيز اول صفحتين  من المشروع , اذا كان عندكم sign in خلو اخر شي، يفضل ان تبدوا Home Screen
4. قم بصنع **Struct** خاص في برنامجك 
- مثلا اذا كان مشروعك عن حجز مطاعم
<div dir="ltr">


```Swift  

struct Restaurant
{
    var restaurantName :String
    var restaurantLocation :String
    var availableTable : Int
    var restaurantImage :String
}

struct RestaurantCategory
{
    var cateogry : String
    var restaurantList : [Restaurant]
    var catogryImage : String
}

```
</div>

5. بعدها تعمل array of struct و تحتوي على جميع المعلومات لاستخدامها في التطبيق

<div dir="ltr">

```Swift

var categories : [RestaurantCategory] =
[RestaurantCategory(cateogry: "Italian", restaurantList: [
                        Restaurant(restaurantName: "Pastamania", restaurantLocation: "Kuwait City", availableTable: 5, restaurantImage: "pastamania"),
                        Restaurant(restaurantName: "Patio", restaurantLocation: "Avenue", availableTable: 9, restaurantImage: "patio")], catogryImage:  "Italian"),
 RestaurantCategory(cateogry: "Burger", restaurantList: [
                        Restaurant(restaurantName: "Elevation Burger", restaurantLocation: "kuwait City", availableTable: 8, restaurantImage: "elevation")], catogryImage: "burger")]


```
</div>





</div>
