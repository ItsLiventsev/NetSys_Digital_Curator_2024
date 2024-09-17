# ДУП.01 Цифровой куратор @pk8.mscobr@pk8.mskobr

# Практические задания для самостоятельной работы

Практические задания по курсу - https://github.com/ItsLiventsev/NetSys_Digital_Curator_2024/tree/main/Praktika

# Практические задания, который делали совместно со мной

## Часть 1. УП.04. 1. Создание, тестирование и защита паролей

### Задание 1. Обучающемуся дана легенда: вы студент первого курса, будущий консультант в области цифровой грамотности. Ваша задача — научиться создавать, тестировать и защищать пароли, чтобы в дальнейшем обучать этому других. Сегодняшнее занятие даст вам базовые знания и навыки, необходимые для обеспечения безопасности в цифровом мире.

Для начала выполнения заданий перейдите по следующей ссылке -https://github.com/kvinokain/DUP01/blob/main/Praktika/YP01/YP01.md

#### Что такое пароль?

Пароль — это секретная комбинация символов, используемая для подтверждения личности пользователя и защиты доступа к учетной записи, устройству или системе. Пароли могут включать буквы, цифры и специальные символы. Надежные пароли сложны, длинны и уникальны, что делает их трудными для подбора. Использование паролей — один из основных методов защиты личных данных и предотвращения несанкционированного доступа в цифровом мире.

#### В чем опасность использования слитых паролей?

Кража личных данных: Злоумышленники могут получить доступ к вашим личным и финансовым данным, включая адреса, номера банковских карт и другую конфиденциальную информацию.

Неавторизованный доступ: Слитые пароли позволяют злоумышленникам войти в ваши учетные записи на различных платформах, что может привести к краже аккаунтов, личной информации и даже денег.

Массовые атаки: Злоумышленники могут использовать слитые пароли для так называемых «атаки с заполнением учетных данных» (credential stuffing), где они автоматически пытаются войти в учетные записи на различных сайтах, используя ваши украденные пароли.

Угрозы репутации: Если злоумышленники получают доступ к вашей электронной почте или социальным сетям, они могут распространять ложную информацию, угрожать вашему личному и профессиональному имиджу.

Цепная реакция: Если вы используете один и тот же пароль для разных учетных записей, утечка одного пароля может поставить под угрозу все связанные с ним аккаунты.

В каждой легенде есть инструкция по выполнению работы -https://github.com/kvinokain/DUP01/blob/main/Praktika/YP01/YP01.md

### Задание 2. Обучающемуся дана легенда: Вам успешно удалось создать свой необычный и запоминающийся пароль! Однако, теперь перед вами стоит более сложная задача. С помощью игры от "OverTheWire" и команд Linux терминала вам предстоит продвигаться все дальше и дальше в систему, решая задачи по безопасности и улучшая свои навыки работы с паролями.

Для начала выполнения заданий перейдите по следующей ссылке - https://github.com/kvinokain/DUP01/blob/main/Praktika/YP01/Task%202%20P%40ssw0rd.md

#### Что такое Linux?

Linux — это свободная и открытая операционная система, основанная на ядре Linux. Она является альтернативой коммерческим операционным системам, таким как Windows и macOS. В особенности этой операционной системы входит, то что это многопользовательская, многозадачная система с высокой степенью безопасности и стабильности. Используется в серверах, ПК, встраиваемых системах и мобильных устройствах.

#### Зачем нужен терминал?

Терминал в Linux – это инструмент, который позволяет производить настройку систему с помощью команд. Системные администраторы ценят в терминале 3 фактора: Скорость работы (Нет траты ресурсов на графическое отображение) Гибкость команд (Возможность комбинирования и применение ключей); Широкие возможности автоматизации на языке Bash.

#### Примеры использования терминала

![image](https://github.com/user-attachments/assets/d5c5b4d1-d479-4f99-ba43-4776de2bef37)

![image](https://github.com/user-attachments/assets/10b5e636-cb10-47da-85a3-d3f01d9f1059)

##### Дополнительные команды и утилиты, которые использовали

su - команда Unix-подобных операционных систем, позволяющая пользователю войти в систему под другим именем, не завершая текущий сеанс.

mc - *Midnight Commander) — это текстовый файловый менеджер для командной строки.

Для входа в mc вписываем в терминале mc

![image](https://github.com/user-attachments/assets/c58216bd-54b8-4744-a9d3-f2acde0e2a52)

Открывается утилита

![image](https://github.com/user-attachments/assets/e51a9c82-20b2-44cf-9d67-f6c50e6d923f)

В утилите у нас два "рабочих окна", чтобы между ними перемещаться нажимаем - TAB

Снизу есть помощь в виде команад:

![image](https://github.com/user-attachments/assets/41cfeaa3-e586-4a45-b1cd-d85e24e2a696)

Вводить команды через "F" - т.е. F1, F2, F3, F4, F5, F6 и т.д.

mcedit - (Midnight Commander edit) — это текстовый редактор для командной строки.

![image](https://github.com/user-attachments/assets/c7996b8f-341f-49a5-a729-9e77e40278e9)

Также можно открыть сразу файл через mcedit

![image](https://github.com/user-attachments/assets/bcc499bd-c7f4-42c4-be99-bf195ac8603c)

Ввод данных в файл проводится "стандартно"

![image](https://github.com/user-attachments/assets/641d8fc1-60dd-4e48-84d1-84c72c6d8da2)

Также есть меню помощи снизу

![image](https://github.com/user-attachments/assets/861249ef-e0af-431d-a2e1-abcbcc042e21)

rm - удалить файл

rmdir - удалить папку (директорию)
