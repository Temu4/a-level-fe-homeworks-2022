1 + 1   //number , два числа = число 
'1' + 1 //string , если один из елементов строка то неявно приводиться к строке
1 + [2] //number неявное привидение типа к числу 
1 + {}  //number неявное привидение типа к числу несмотря на то что 2 елемент object 
2 - {}  //Boolean   не можем привести  в число из за '-'
+ 'a'   //number неявное преобразование строки в число
+ ''    //number неявное преобразование строки в число
+ '-1'  //number неявное преобразование строки в число
+ {}    //number неявное преобразование object в число
1 + 'a' //number неявное преобразование строки в число с первым елементом числом
1 + {}  //number так же как и в 4 примере , неявное приведение  в число
[] + [] //string так как у нас из двух елементов нет ни одного числа мы не можем неявно привести к числу , и неявно переводим в строку
1 - 'a' //Boolean неявное преобразование не получиться так как "-"
1 - {}  //Boolean неявное преобразование не получиться так как "-"
[] - [] //Boolean не получиться даже object в связи с "-"
