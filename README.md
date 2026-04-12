# Инструкция по установке и настройке через скрипт:

- в **SSH** запустите скрипт:
```
sh <(wget -O - https://raw.githubusercontent.com/StressOzz/Mixomo-Manager/main/Mixomo-Manager.sh)
```

- Установите **Mixomo**

   При установки **MagiTrickle** появится меню выбора версии: `Оригинальный MagiTrickle` или `MagiTrickle badigit mod`
   
   Для обычного пользователя достаточно `Оригинальной версии`

- Интегрировать **VPN** подписку в **Mihomo**

   Вставьте ссылку на свою подписку.
   Может воспользоваться тестовой подпиской https://github.com/StressOzz/Mixomo-Manager/issues/16
   
- Сгенерируйте **WARP** 
 
   Для генерации **WARP** через скрипт понадобится установить **[Zapret](https://github.com/StressOzz/Zapret-Manager)**
   
- Интегрируйте **WARP**

   Для интеграции своего **WARP** файла - скиньте его в `/root/WARP.conf`
   
- Зайдите на http://192.168.1.1:8080/ выберите списки, которые Вам нужны, нажмите **Сохранить изменения**

- Зайдите на http://192.168.1.1:9090/ui 
   в поле **Хост** введите 192.168.1.1
   во вкладке **Прокси** выберите **Сервер для YouTube** и **Сервер для остального трафика** который поёдйт через списки **MagiTrickle**

```
Меню 
1) Установить Mixomo
2) Удалить Mixomo
3) Сменить список MagiTrickle
   1) Список от ITDog
   2) Список от Internet Helper
4) Интегрировать VPN подписку в Mihomo / Сменить VPN подписку
5) Сгенерировать WARP в /root/WARP.conf
6) Интегрировать /root/WARP.conf в Mihomo
```

---

[<img width="190" height="175" alt="donate-button-click-donation-charity-600nw-2339825981" src="https://github.com/user-attachments/assets/2999757b-fbf3-4149-bf6c-48bf3e241529" />](https://github.com/StressOzz#-поддержать-проект)

---

# Благодарности

Спасибо [Internet Helper](https://github.com/Internet-Helper/) за [Mixomo](https://github.com/Internet-Helper/mixomo-openwrt)
