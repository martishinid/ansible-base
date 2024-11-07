# Домашнее задание к занятию 1 «Введение в Ansible»

Основная часть:

1. Запуск playbook из окружения на окружении из `test.yml`

Команда: `ansible-playbook site.yml -i inventory/test.yml`

Значение факта для хоста: 12

2. Поменял в examp.yml Значение переменной `some_fact` с 12 на all default fact 

![Задание 2](images/2.png)

3. Подготовленное окружение:

![Задание 3](images/3.png)

4. Запуск playbook из окружения на окружении из `prod.yml`

![Задание 4](images/4.png)

5. Изменение значение переменной:

![Задание 5](images/5.png)

6. Повтор запуска playbook:

![Задание 6](images/6.png)

7. Шифрование переменных с помощью `ansible-vault`

![Задание 7](images/7.png)

8. Повтор запуска playbook:

![Задание 8](images/8.png)

9. `ansible-doc -t connection -l`
Подойдет Local

![Задание 9](images/9.png)

10. Обновленный prod.yml

![Задание 10](images/10.png)

11. Повтор запуска playbook:

![Задание 11](images/11.png)

