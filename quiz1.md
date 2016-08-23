# สรุปควิซคอมโปร

> "ไม่ทราบครับ...แต่ถ้าจะควิซก็ไม่ควรมาบอกเอาตอน 5 ทุ่มรึเปล่า..." – ไข่

## Input and output

### Output
* ` Console.Write()` และ `Console.WriteLine()`
    * `Console.Write(a + "\n")` == `Console.WriteLine(a)`
    * `Console.WriteLine("{0:0.0000}", a)` จะพิมพ์ a ที่ทศนิยม 4 ตำแหน่ง
* `Console.Read()`
    * Return ค่าเป็น char
        * char ทำ implicit/explicit convert เป็น int ได้
            * (เช่น) `int a = Console.Read()` เป็น implicit convert
*  `Console.ReadLine()`
    * Return ค่าเป็น string
        * string to char
            * ให้มี `string str = "a";`
            * `char m = (char)str[0];`

## Datatypes
ไปท่องเอง

## Arithmatic operators
* Return ค่าที่ precise ที่สุด (bit เยอะที่สุด)
    * ทำ explicit datatype ได้
* __PEMDAS__
    * Parenthesis, Exponential, Multiplication and Division, Addition and Subtraction

## Boolean operators
* and (`&&`)
* or (`||`)
* ประพจน์ที่ควรรู้
    * p -> q == ~p v q
    * p <-> q == (~p v q) ^ (~q v p)
* __ใช้ `==` แทนการเท่ากัน__
    * `=` คึือ assignment
