# BASIC-CSharp
# พื้นฐานภาษา C#

## [1.ส่วนประกอบของภาษา](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#%E0%B8%AA%E0%B9%88%E0%B8%A7%E0%B8%99%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%81%E0%B8%AD%E0%B8%9A%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2)
* [Identifiers](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#identifiers)
* [คำสงวน (Keywords)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%87%E0%B8%A7%E0%B8%99-keywords)
* [Contextual keywords]	(https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#contextual-keywords)
* [อักษรว่าง Whitespac](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#%E0%B8%AD%E0%B8%B1%E0%B8%81%E0%B8%A9%E0%B8%A3%E0%B8%A7%E0%B9%88%E0%B8%B2%E0%B8%87-whitespace)
* [Statements](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#statements)	
* [Block](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C-Sharp-Language#block)
 
 
## [2. ตัวแปรและชนิดของข้อมูล Variables and Types](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B9%81%E0%B8%9B%E0%B8%A3%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%8A%E0%B8%99%E0%B8%B4%E0%B8%94%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B8%B9%E0%B8%A5-variables-and-types)
* [ข้อมูลชนิดตรรกะ The Boolean Type](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B8%B9%E0%B8%A5%E0%B8%8A%E0%B8%99%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%A3%E0%B8%A3%E0%B8%81%E0%B8%B0-the-boolean-type)
* [ชนิดข้อมูลตัวเลข (Integer Types)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%8A%E0%B8%99%E0%B8%B4%E0%B8%94%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B8%B9%E0%B8%A5%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B9%80%E0%B8%A5%E0%B8%82-integer-types)
* [ชนิดข้อมูลเลขทศนิยม (Floating Point and Decimal Types)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%8A%E0%B8%99%E0%B8%B4%E0%B8%94%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B8%B9%E0%B8%A5%E0%B9%80%E0%B8%A5%E0%B8%82%E0%B8%97%E0%B8%A8%E0%B8%99%E0%B8%B4%E0%B8%A2%E0%B8%A1-floating-point-and-decimal-types)
* [ข้อความ (String Type)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1-string-type)
* [ตัวแปรและค่าคงที่ (Variable and constant)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B9%81%E0%B8%9B%E0%B8%A3%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%84%E0%B9%88%E0%B8%B2%E0%B8%84%E0%B8%87%E0%B8%97%E0%B8%B5%E0%B9%88-variable-and-constant)
* [Enumeration	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#enumeration)
* [สมการ (Expression)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%AA%E0%B8%A1%E0%B8%81%E0%B8%B2%E0%B8%A3-expression)
* [คำสั่ง (Statement)	](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Variables-and-Types#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-statement)

## [3. การเปลี่ยนทิศทางการทำงานของโปรแกรม](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9B%E0%B8%A5%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%99%E0%B8%97%E0%B8%B4%E0%B8%A8%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%97%E0%B8%B3%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%81%E0%B8%81%E0%B8%A3%E0%B8%A1)
* [การเปลี่ยนทิศทางแบบไม่มีเงื่อนไข](	https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9B%E0%B8%A5%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%99%E0%B8%97%E0%B8%B4%E0%B8%A8%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B8%A1%E0%B8%B5%E0%B9%80%E0%B8%87%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%82)
* [การเปลี่ยนทิศทางแบบมีเงื่อนไข (Conditional Branching) ](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9B%E0%B8%A5%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%99%E0%B8%97%E0%B8%B4%E0%B8%A8%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B8%A1%E0%B8%B5%E0%B9%80%E0%B8%87%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%82-conditional-branching)
 * [คำสั่ง if](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-if)
 * [คำสั่ง if…else](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-ifelse)
 * [คำสั่ง if ซ้อนกัน (nested if)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-if-%E0%B8%8B%E0%B9%89%E0%B8%AD%E0%B8%99%E0%B8%81%E0%B8%B1%E0%B8%99-nested-if)
 * [คำสั่ง if…else…if](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-ifelseif)
 * [คำสั่ง Switch](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Branch#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-switch)
* [คำสั่งควบคุมการวนรอบ (Iteration statement)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87%E0%B8%84%E0%B8%A7%E0%B8%9A%E0%B8%84%E0%B8%B8%E0%B8%A1%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%A7%E0%B8%99%E0%B8%A3%E0%B8%AD%E0%B8%9A-iteration-statement)
 * [คำสั่ง While](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-while)
 * [คำสั่ง do…while](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-dowhile)
 * [คำสั่ง for](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-for)
 * [คำสั่ง break](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-break)
 * [คำสั่ง continue](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-continue)
 * [คำสั่ง foreach…in](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Iteration-statement#%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-foreachin)

##  [4.	ตัวดำเนินการ (Operators)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3-operators)
* [ตัวดำเนินการกำหนดค่า (Assignment Operators)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%81%E0%B8%B3%E0%B8%AB%E0%B8%99%E0%B8%94%E0%B8%84%E0%B9%88%E0%B8%B2-assignment-operators)
* [ตัวดำเนินการทางคณิตศาสตร์ (Methematical Operators)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B8%84%E0%B8%93%E0%B8%B4%E0%B8%95%E0%B8%A8%E0%B8%B2%E0%B8%AA%E0%B8%95%E0%B8%A3%E0%B9%8C-methematical-operators)
* [ตัวดำเนินการเพิ่มค่า/ลดค่า ครั้งละ 1 หน่วย (Incremental/Decremental)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%84%E0%B9%88%E0%B8%B2%E0%B8%A5%E0%B8%94%E0%B8%84%E0%B9%88%E0%B8%B2-%E0%B8%84%E0%B8%A3%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%A5%E0%B8%B0-1-%E0%B8%AB%E0%B8%99%E0%B9%88%E0%B8%A7%E0%B8%A2-incrementaldecremental)
* [ตัวดำเนินการเพิ่ม/ลดค่า (Calculate & reassign operator)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%A5%E0%B8%94%E0%B8%84%E0%B9%88%E0%B8%B2-calculate--reassign-operator)
* [Prefix/Postfix operator](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#prefixpostfix-operator)
* [ตัวดำเนินการเปรียบเทียบ (Relational Operators)](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#%E0%B8%95%E0%B8%B1%E0%B8%A7%E0%B8%94%E0%B8%B3%E0%B9%80%E0%B8%99%E0%B8%B4%E0%B8%99%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9B%E0%B8%A3%E0%B8%B5%E0%B8%A2%E0%B8%9A%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B8%A2%E0%B8%9A-relational-operators)
* [Operator Precedence](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#operator-precedence)
* [The ternary operator](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/Operators#the-ternary-operator)

## [5. อื่นๆ / Advanced features](https://github.com/Desktop-Programming-Lab-2559/KB-BASIC-CSharp/wiki/C%23-Language-Features#c-language-features)


