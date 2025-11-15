# Telcom Customer Churn

Каждая строка содержит описание клиента. Исходный датасет содержит 7043 строки и 21 признак. "Churn" - целевая переменная. 

| Variable   |	Description |
|------------|----------------|
|Customer ID | ID пользователя|
|Gender      | Пол пользователя|
|SeniorCitizen|Пенсионер (1, 0) |
|Partner    | Есть ли у пользователя пара|
|Dependents |Есть ли у пользователя Иждивенец (Yes, No)|
|tenure     |Количество месяцев, в течение которых клиент пользуется услугами|
|PhoneService|Пользуется ли клиент сервисами(Yes, No)|
|MultipleLines|Имеет ли клиент несколько линий или нет(Yes, No, No phone service)|
|InternetService|Интернет-провайдер клиента(DSL, Fiber optic, No)|
|OnlineSecurity|Пользуется ли клиент онлайн безопасностью (Yes, No, No internet service)|
|OnlineBackup|Есть ли у клиента онлайн-резервное копирование или нет(Yes, No, No internet service)|
|DeviceProtection|Имеет ли клиент защиту устройства или нет (Yes, No, No internet service)|
|TechSupport|Есть ли у клиента техническая поддержка или нет (Yes, No, No internet service)|
|StreamingTV|Есть ли у клиента online телевидение или нет (Yes, No, No internet service)|
|StreamingMovies|Есть ли у клиента online кинотеатр или нет (Yes, No, No internet service)|
|Contract|Срок действия договора с заказчиком (Month-to-month, One year, Two year)|
|PaperlessBilling|Имеет ли клиент электронный счет или нет (Yes, No)|
|PaymentMethod|Способ оплаты (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))|
|MonthlyCharges|Сумма, взимаемая с клиента ежемесячно|
|TotalCharges|Общая сумма, взимаемая с клиента|
|Churn|Ушел клиент или нет (Yes or No)|