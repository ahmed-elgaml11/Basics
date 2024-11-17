# CH3 Dataase.. Data Modelling Using The Entity Relationship (ER) model.
### ال ER MODL:
**نموذج يستخدم لتمثيل الكيانات التي نحتفظ عنها ببيانات والعلاقات بينها**

### الEntity:
**هو اي شخص او مكان او حدث او شيئ  يهتم المستخدم يحفظ بياناته في قاعده البيانات**

### الAttributes: 
**هي الخصائص او البياتات التي يتم تخزينها عن كل entity...(name,address,data,email...)**

___
 
## Clssification of attributes:.
- ![2](.//pics/2.png)
- ![1](.//pics/1.png)
- ![4](./pics//4.png)
- ![3](./pics//3.png)
- ![5](.//pics/5.png)
- ![6](.//pics/6.png)
  
## How to Draw ER Model
![7](.//pics/7.png)  
`e`:entity `k`:ket attribute `c`: compsite att `m`: multi valued att `d`:derived att
___
## Relationships: 
**degree of realtionships:** refers to the nunber of entities.
- `binary`: between two entities. 
- `ternary`: between three entities.
   
**recusive relationship:**  between the entity and itself.


## constrains on relationships:

- **cardinality of relationships:**
![8](.//pics/8.png)

- **participation constrains مشاركه**
  
لو لازم كل الentity تشارك في العلاقه بحط double line ويبقي اسمه total participation

لو مش لازم كل اللي في الentity يشارك بحط single line ويبقي اسمه partial participation

- **(min,max)notation:** 
  
   كل عنصر في الentity يقدر يشارك علي الاقل كام مره وعلي الاكثر كام مره

   ___
  ## Example on ER diagram>>>THE COMPANY
  ![10](.//pics/10.png)
  ![9](./pics//9.png)
  ![11](.//pics/111.png)
  ## طب ازاي احول الERD الي SCHEMA
1.  بعمل لكل entity جدول
1.  بعمل لكل  multivalued attribute جدول وبحط فيه ال key attribute بتاع ال entity الرئيسي ويبقي هم الاتنين primary key
1.  بعمل لكل علاقه M:N جدول وبحط فيه ال pk بتاع الاتنين entities بتوعها واي attribute موجود علي العلاقههههه
2.  لكل علاقه  M:1 بنقل ال PKEY من ال 1 الي M
3.  لكل علاقه 1: 1 بنقل ال PKEY من ال partial participation الي ال total participation
4.   مبكتبش ال composite attribute بكتب بس ال الفروع بتاعته
5.   لو عندي entity ليه اكتر من key بختار منهم 1 بس
6.   لو فيه attribute موجود علي علاقه بنقله لل entity اللي عنده total participatioj
   ___
