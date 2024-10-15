Основы Linux
Создание директории devops_test в домашнем каталоге. Чтобы создать директорию devops_test в вашем домашнем каталоге, выполните следующую команду в терминале:
mkdir ~/devops_test
Создание пустого файла readme.txt в созданной директории. После создания директории мы можем создать пустой файл readme.txt в ней:
touch ~/devops_test/readme.txt
Показать текущий путь в терминале. Чтобы узнать текущий путь, используйте команду:
pwd

2. Основы Git
Создайте новый локальный репозиторий. Перейдите в директорию devops_test и инициализируйте новый репозиторий:
cd ~/devops_test
git init
Создайте файл test.txt, добавьте в него текст “Hello DevOps”. Теперь создайте файл test.txt и добавьте в него текст:
echo "Hello DevOps" > test.txt
Закоммитьте изменения с сообщением “Initial commit”. Добавьте файл в индекс и выполните коммит:
git add test.txt
git commit -m "Initial commit"
Покажите историю коммитов. Чтобы увидеть историю коммитов, выполните:
git log

4. Основы сетевых технологий
Что такое IP-адрес и для чего он используется? IP-адрес (Internet Protocol address) — это уникальный адрес, который идентифицирует каждое устройство в сети.
Он необходим для маршрутизации данных между устройствами в интернете, позволяя им находить друг друга и обмениваться информацией.
Назовите основные отличия между протоколами TCP и UDP.
TCP (Transmission Control Protocol):
Устанавливает соединение перед передачей данных.
Обеспечивает надежную доставку и последовательность пакетов.
Более медленный из-за механизма подтверждения получения.
UDP (User Datagram Protocol):
Не устанавливает соединение, данные отправляются без предварительного согласования.
Не гарантирует доставку или порядок получения пакетов.
Быстрее, что делает его подходящим для потокового видео или онлайн-игр.

4. Программирование (Bash или Python)
Напишите скрипт на Bash или Python, который выводит числа от 1 до 10.
На Bash:
for i in {1..10}
do
  echo $i
done

На Python:
for i in range(1, 11):
    print(i)
    
5. Логическое мышление
В одном здании находится три лампочки, управляемые тремя выключателями в другой комнате.
Как определить, какой выключатель к какой лампочке относится, если вы можете зайти в комнату с лампочками только один раз?
Решение:
Включите первый выключатель и подождите 10-15 минут.
Выключите первый выключатель и включите второй.
Затем зайдите в комнату с лампочками:
Лампочка, которая горячая, соответствует первому выключателю.
Лампочка, которая светится, соответствует второму выключателю.
Лампочка, которая холодная и не светится, соответствует третьему выключателю.
