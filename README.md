# Документация к проекту
Сервис по продаже и покупке домашних животных.
Необходимо спроектировать систему для продажи животных “Котопес”, которая должна автоматизировать процесс 
приобретения и сдачи домашних животных. Система должна включать в себя возможность регистрации пользователя, 
размещения анкет животных в каталоге на продажу или передачу в добрые руки, возможность покупки животного, а 
также логистическую службу доставки оного. 
Зарегистрированный пользователь может как размещать обьявления, так и приобретать животных. 
Процесс выбора заключает в себе выбор клиентом животного путем сортировки из списка с применением фильтров: 
вид животного, порода, возраст, вес и прочие сопутствующие характеристики. 
Клиент может связаться с продавцом посредством видеосвязи для осмотра реального внешнего вида животного и 
уточнения возникших вопросов (рацион питания и т. д.), номера телефона, если тот будет указан в аккаунте, а 
также внутреннего чата между продавцом и возможным покупателем. 
После определения желаемого животного составляется договор купли – продажи, в котором указывается порода 
собаки, сумма покупки, дата оформления, а также номер паспорта животного. 
Паспорт животного содержит в себе полную информацию о животном, в том числе даты прививок, генетические 
данные о родителях. 
Далее продавец договаривается с клиентом о способе доставки питомца (самовывоз либо доставка службой логистики) 
и назначает удобное время для клиента. 

МЕХАНИЗМ ПРИОБРЕТЕНИЯ: 
<li>Клиент регистрируется в системе, после авторизации пользователь получает доступ к личному кабинету и каталог животных.  
Процесс выбора заключает в себе выбор клиентом животного путем сортировки из списка с применением фильтров: вид
животного, порода, возраст, вес и прочие сопутствующие характеристики. </li>
<li>Клиент может связаться с продавцом посредством видеосвязи для осмотра реального внешнего вида животного и уточнения
возникших вопросов (рацион питания и т. д.), номера телефона, если тот будет указан в аккаунте, а также внутреннего
чата между продавцом и клиентом. </li>
<li>После определения желаемого животного составляется договор купли – продажи, в котором указывается порода собаки, сумма
покупки, дата оформления, а также номер паспорта животного. 
Паспорт животного содержит в себе полную информацию о животном, в том числе даты прививок, генетические данные о родителях. </li>
<li>Далее продавец-консультант договаривается с клиентом о способе доставки питомца (самовывоз либо доставка службой логистики)
и назначает удобное время для клиента. </li>

МЕХАНИЗМ ПРОДАЖИ: 
<li>Клиент регистрируется в системе, после авторизации пользователь получает доступ к личному кабинету, в котором заполняет
заявку на продажу питомнику животного. </li>
<li>В заявке указывается анкета питомца, включая все его характеристики и паспорт животного. </li>
<li>Редактор рассматривает оставленную заявку и подтверждает размещение анкеты на сайте. </li>

 -------------------------------------------------------------------------------------------------------------------------------------------------
 ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ:
 
 Незарегистрированный пользователь:
 
<li>Система должна позволять незарегистрированному пользователю проходить процедуру создания аккаунта с использованием логина и пароля. </li>
<li>Система должна позволять незарегистрированному пользователю просматривать каталог животных с применением фильтров сортировки. </li>
<li>Система должна позволять незарегистрированному пользователю просматривать анкеты животных. </li>

Зарегистрированный пользователь-покупатель - объединить продавца и покупателя 	

Требования пользователя с ролью «Незарегистрированный пользователь» соответствуют требованиям пользователя с ролью “Незарегистрированный пользователь” (за исключением 1 пункта). 
Система должна позволять клиенту оставлять заявку на приобретение животного. 
Система должна позволять клиенту выбирать тип и время доставки питомца. 
Система должна позволять клиенту заключать договор купли-продажи. 
Система должна позволять общаться клиенту с продавцом посредством чата, который прикреплен к определенной анкете.
Система должна позволять клиенту создавать заявку на продажу животного. 
Система должна позволять клиенту создавать анкету животного. 
Система должна позволять клиенту просматривать статус заявки - в обработке, проходит модерацию, прошла модерацию. 
Система должна позволять клиенту заключать договор купли-продажи. 

--------------------------------------------------------------------------------------------------------------------------------------------------
ДИАГРАММА КЛАССОВ (делал заказчик):

![диаграмма классов, делал заказчик](https://user-images.githubusercontent.com/76678991/224638442-43c30e03-a99c-4848-ae6d-f2ae840704a6.png)
