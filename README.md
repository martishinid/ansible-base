# Домашнее задание к занятию 1 «Введение в Ansible»

Основная часть:

1. Запуск playbook из окружения на окружении из `test.yml`

Команда: `ansible-playbook site.yml -i inventory/test.yml`

Значение факта для хоста: 12

2. Поменял в examp.yml Значение переменной `some_fact` с 12 на all default fact 

![Задание 2](images/1.png)

3. Подготовленное окружение:

![Задание 3](images/2.png)

4. Изменение значение переменной:

![Задание 4](images/3.png)

5. Повтор запуска playbook из окружения на окружении из `prod.yml`:

![Задание 5](images/4.png)

6. Шифрование переменных с помощью `ansible-vault`

![Задание 6](images/5.png)

7. Повтор запуска playbook:

![Задание 7](images/6.png)

8. `ansible-doc -t connection -l`
Подойдет Local

![Задание 8](images/7.png)

9. Обновленный prod.yml

![Задание 9](images/8.png)

10. Повтор запуска playbook:

![Задание 11](images/9.png)

