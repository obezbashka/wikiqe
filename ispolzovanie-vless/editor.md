---
description: >-
  VLESS - это подобие шифрованного прокси, маскирующегося под HTTPS трафик.  Вы
  можете использовать любой удобный клиент, главное чтобы он поддерживал ядро
  sing-box.
---

# 🔐 Инструкции к VLESS

В этой инструкции мы порекомендуем два клиента, которые подойдут пользователям в зависимости от их предпочтений **Hiddify** **NekoRay** и **v2rayTun**

<figure><img src="../.gitbook/assets/Снимок экрана 2025-05-16 170746.png" alt=""><figcaption></figcaption></figure>

При желании, вы можете использовать разные клиенты для разных устройств или для разных ситуаций.

### Hiddify <a href="#hiddify" id="hiddify"></a>

<figure><img src="../.gitbook/assets/365962058-d57391ee-d479-4122-9a67-08ecc9db60a3.png" alt=""><figcaption></figcaption></figure>

#### Скачивание <a href="#section" id="section"></a>

| Операционная система | Скачать                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| iOS                  | [![](https://img.shields.io/badge/IPA-Universal-c0c0c0.svg?logo=ios)](https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-iOS.ipa)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Android              | <p><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Android-universal.apk"><img src="https://img.shields.io/badge/APK-Universal-044d29.svg?logo=android" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Android-arm64.apk"><img src="https://img.shields.io/badge/APK-ARMv8-168039.svg?logo=android" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Android-arm7.apk"><img src="https://img.shields.io/badge/APK-ARMv7-45bf55.svg?logo=android" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Android-x86_64.apk"><img src="https://img.shields.io/badge/APK-x64-96ed89.svg?logo=android" alt=""></a></p> |
| Windows              | <p><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Windows-Setup-x64.exe"><img src="https://img.shields.io/badge/Setup-x64-2d7d9a.svg?logo=windows" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Windows-Portable-x64.zip"><img src="https://img.shields.io/badge/Portable-x64-67b7d1.svg?logo=windows" alt=""></a></p>                                                                                                                                                                                                                                                                                                                                                                                     |
| MacOS                | <p><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-MacOS.dmg"><img src="https://img.shields.io/badge/DMG-Universal-ea005e.svg?logo=apple" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-MacOS-Installer.pkg"><img src="https://img.shields.io/badge/PKG-Universal-bc544b.svg?logo=apple" alt=""></a></p>                                                                                                                                                                                                                                                                                                                                                                                                     |
| Linux                | <p><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Linux-x64.AppImage"><img src="https://img.shields.io/badge/AppImage-x64-f84e29.svg?logo=linux" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-Debian-x64.deb"><img src="https://img.shields.io/badge/DebPackage-x64-FF9966.svg?logo=debian" alt=""></a><br><a href="https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-rpm-x64.rpm"><img src="https://img.shields.io/badge/RpmPackage-x64-F1B42F.svg?logo=redhat" alt=""></a></p>                                                                                                                                                                                                    |

#### Подключение <a href="#section-1" id="section-1"></a>

Для подключения скопируйте ссылку профиля, затем нажмите **добавить профиль -> Добавить из буфера обмена**.

По умолчанию для российских пользователей обращения к российским IP и .ru доменам будет происходить напрямую. Если вы хотите направить их через VLESS, перейдите в раздел **Параметры конфигурации** и поменяйте **Регион** на **Другой**

Хорошо работают 2 режима работы:

1. **Системный прокси** (только на десктопных клиентах) - Hiddify прописывается как системный прокси и приложения сами отправляют трафик через него. Тем не менее, некоторые приложения могут отправлять трафик в обход системного прокси.
2. **VPN** - Hiddify создает TUN/TAP интерфейс и работает как VPN, перенаправляя весь трафик через себя. Для этого режима необходим запуск Hiddify с правами администратора. Можно навсегда прописать запрос таких прав в свойствах .exe файла.

### NekoRay <a href="#nekoray" id="nekoray"></a>

<figure><img src="../.gitbook/assets/365968120-39eef7ce-762c-46c1-aba0-a584665e9f47.png" alt=""><figcaption></figcaption></figure>

#### Скачивание <a href="#section-2" id="section-2"></a>

* NekoRay - клиент под Windows/Linux. [**Ссылка для скачивания NekoRay**](https://github.com/MatsuriDayo/nekoray/releases/latest)
* NekoBox - клиент под Android. [**Ссылка для скачивания NekoBox**](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases/latest) (в GooglePlay фейк)

#### Подключение <a href="#section-3" id="section-3"></a>

1. Для подключения скопируйте ссылку профиля, затем нажмите **Программа -> Добавить профиль из буфера обмена**.
2. Чтобы запустить или остановить профиль **ПКМ по профилю -> Запустить/Остановить**
3. Чтобы трафик шел через NekoRay должна быть установлена галочка **Режим TUN** или **Режим системного прокси** (разницу см. в разделе Hiddify). При отключении профиля галочку необходимо убирать, иначе интернет-соединения не будет. Стоит галочка - трафик идет в NekoRay, не стоит идет обычным путем.
4. Настройки фильтрации при необходимости можно добавить в **Настройки -> Настройки маршрутов -> Вкладка Базовые маршруты**. В нижнем правом углу задается назначение трафика, который не соответствует фильтрам. Примеры фильтров можно посмотреть загрузив китайский **Пресет**. Можно создать несколько наборов машрутов (первая вкладка) и переключаться между ними в **Программа -> Активное правило роутинга**.

### FoXray <a href="#foxray" id="foxray"></a>

<figure><img src="../.gitbook/assets/366144435-d3ef6237-ea85-4479-90d3-07395c4cb81c.jpg" alt=""><figcaption></figcaption></figure>

#### Скачивание <a href="#section-4" id="section-4"></a>

[![](https://github.com/user-attachments/assets/007677d2-f5d9-4d1e-bb9e-2c260b3c4e57)](https://apps.apple.com/ru/app/foxray/id6448898396)

Для добавления сервера **скопируйте ссылку профиля**, затем нажмите на кнопку для загрузки ссылки из буфера обмена (**обведена на скриншоте**, самая правая)\
\


## Подключение с Android

* Скачиваем приложение [v2rayTUN](https://play.google.com/store/apps/details?id=com.v2raytun.android\&hl=ru)
* Заходим в [меню управления подпиской](https://wizardvpn.app/profile/vpns) и нажимаем "Подключиться"
* Вас перекинет на выбор подключения, мы нажимаем на "Скопировать ключ"

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

* Вам нужно зайти в приложение **v2rayTUN** и сверху справа нажать на **"+"**, после на **"Вставить из буфера обмена"**
* После этих действий профиль появится в приложении, останется только подключиться

<figure><img src="../.gitbook/assets/image (1)1.png" alt=""><figcaption></figcaption></figure>
