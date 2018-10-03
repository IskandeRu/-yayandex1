# -yayandex1
Just testing some tables to understand my knowledge 


"Select" 
Select orderId, ProductId, UnitPrice 
from orderdetails
where orderId>5  ( условие ) 

Create Table YANDEXXXDAY1 ( креэйт таблицы ) 

        @Primary Keys have to be smth in dat string 
INSERT INTO YANDEXXXDAY1 ( ID, Name, Surname ) 
Values ('1','Alex','kamenkov');

      @Create temporary table ( Faster but deleted when session will be ended ) 
Create temporary table Alexander as 
( Select * from onedatabase where Kamenkovage>24 ); 


      @ how to comment correctly
Select surname /* vot tut budet comment */
-- vot tak eshe mozhno komment ostavit

from studenti

https://www.coursera.org/learn/sql-for-data-science/lecture/GAA9h/module-introduction


      @Filtering
WHERE Age IN(10,11,12) /* age will be only 10,11,12 */ 

WHERE surname='Ivanov' or surname='Ivankov' /* we will see only strings with surname ivanov and ivankov */

AND name='Ivan' /* will be only Ivan Ivanov or Ivan Ivankov */

NOT age='18' /* will be only Ivan Ivanov, because Ivan Ivankov is 18 years old */

      @wildcards
      
'%Kamenkov' /* all names before Kamenkov
'%Kamenkov%' /* all names before and after Kamenkov
'Kamenkov%' /* All names after Kamenkov

      @Sorting
Order by name /* sorted by the name 
Asc /* po vozrastaniu
desc /* po ubivaniu


AVG()
SUM
COUNT
MIN
MAX
DISTINCT

Group by /* группируют по ключу
Having /* группируют не по ключу

Select name, Count (*) as countant
from database
group by name
having count(*)>2
Group by name

Finish 



