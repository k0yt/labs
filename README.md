# labs


https://stepik.org/course/169003

### Этапы проведения атак и компрометации информационных систем

Общий набор этапов для проведения атак и успешной компрометации произвольной информационной системы:
![image](https://github.com/k0yt/labs/assets/114695070/8fb7e35b-8dd7-48c8-9eac-503eba1cb4fc)

### Типовая инфраструктура компании
Рассмотрим схему типовой инфраструктуры организации, которая может подвергаться атакам. На примере подобной инфраструктуры мы будем изучать, какой путь проходят хакеры в целом и белые хакеры при имитации атак.

![image](https://github.com/k0yt/labs/assets/114695070/30b8e3cc-df9d-4bbe-8208-c8dace904999)

### Этапы, которые проходит аудитор для достижения цели:

1. **Разведка во внешней сети. Поиск ресурсов организации**
   1. Активный - Поиск доменных имен
   2. Пассивный - Поиск аккаунтов сотрудников (OSINT)
2. **Атаки первичного доступа**
   1. Компрометация сетевых сервисов (веб-приложений), возможная в результате ошибок конфигурации или разработки
      - Уязвимости обхода аутентификации
      - Уязвимости инъекции команд ОС
      - Уязвимости SQL-инъекции
      - Эксплуатация уязвимости при помощи фреймворка
   2. Фишинг с применением методов социальной инженерии на персонал компании
   3. Переиспользование учетных данных сотрудников компании (почта, домен, облачные сервисы, привилегированные учетные записи), полученных через утечки. ("credential stuffing" – так называется переиспользование утекших учетных данных)
   4. Атаки на внутреннюю сеть, Wi-Fi точки доступа
3. **Закрепление доступа**
   1. Получение легитимного доступа к системе - Backdoor
4. **Повышение привилегий**
   1. Повышение привилегий на серверных системах в Linux

# НЕОБЯЗАТЕЛЬНО
5. Выход за рамки демилитаризованной зоны (ДМЗ) и ограничений сети
6. Проброс трафика в другие сегменты
7. Разведка в локальной сети
8. Захват управления инфраструктурой сети
9. Противодействие обнаружению и реагированию
