# 🐾 Pet Manager — Учёт домашних животных 🐕🐈
# Pet Manager - Командная разработка (ЛР №3)

**Участники команды:**
- @anyveh
- @pechegurovapolina7-pixel

**Калькулятор функций:**
- `add(a, b)` - сложение
- `subtract(a, b)` - вычитание
- `multiply(a, b)` - умножение

## Запуск
```bash
python calculator_add.py
python calculator_subtract.py
python calculator_multiply.py


### *Забота о ваших питомцах в несколько кликов*

---

## 📖 **О проекте**

<div align="center">
  <img src="https://images.unsplash.com/photo-1450778869180-41d0601e046e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="Собака и кошка вместе" width="600" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); margin-bottom: 15px;">
  
  **Pet Manager** — это простое и удобное приложение для учёта домашних питомцев. Оно помогает владельцам хранить информацию о животных, контролировать график прививок и записывать визиты к ветеринару.

  > 💡 *"С заботой о тех, кого приручили"*
</div>

---

## 🎯 **Пример интерфейса**

<div align="center">
  <img src="https://images.unsplash.com/photo-1583511655857-d19b40a7a54e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="Счастливая собака" width="600" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <p><em>Всё о вашем питомце в одном месте</em></p>
</div>

---

## ✨ **Возможности**

Приложение позволяет:

| Иконка | Возможность | Описание |
|:------:|:------------|:---------|
| 📋 | **Карточки животных** | Храните полную информацию о каждом питомце |
| 💉 | **Учёт прививок** | Фиксируйте сделанные прививки и планируйте следующие |
| 🏥 | **Визиты к ветеринару** | Ведите журнал посещений с причинами и заметками |
| 📅 | **Календарь событий** | Отслеживайте предстоящие прививки и визиты |
| 🖼️ | **Загрузка фото** | Добавляйте фотографии питомца в карточку |

---

## 🖼️ **Пример карточки питомца**

<div align="center">
  <img src="https://images.unsplash.com/photo-1543466835-00a7907e9de1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="Собака с ошейником" width="600" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <p><em>Пример карточки питомца с фото и основной информацией</em></p>
</div>

---

## 📦 **Сущности проекта**

### 1. **Питомец**

Основная единица учёта:

| Поле | Описание | Пример |
|:----|:---------|:-------|
| Кличка | *Имя питомца* | `Рекс` |
| Вид | *Собака, кошка и т.д.* | 🐕 Собака |
| Порода | *Порода животного* | `Немецкая овчарка` |
| Дата рождения | *День появления на свет* | `15.05.2020` |
| Фото | *Изображение питомца* | `rex.jpg` |

---

### 2. **Прививка**

Медицинская информация:

| Поле | Описание | Пример |
|:----|:---------|:-------|
| Название | *Тип прививки* | `Бешенство` |
| Дата проведения | *Когда сделана* | `10.01.2024` |
| Следующая дата | *Когда повторить* | `10.01.2025` |

---

### 3. **Визит к ветеринару**

История посещений:

| Поле | Описание | Пример |
|:----|:---------|:-------|
| Дата | *Когда были* | `25.02.2024` |
| Причина | *Зачем пришли* | `Плановый осмотр` |
| Заметки | *Рекомендации врача* | `Здоров, сменить корм` |

---

### 4. **Календарь событий**

Примеры предстоящих событий:

*   💉 **15.06.2024** — Прививка от бешенства (Рекс)
*   💉 **20.06.2024** — Комплексная прививка (Мурка)
*   🏥 **25.06.2024** — Плановый осмотр (Все питомцы)
*   💉 **01.07.2024** — Ревакцинация (Барсик)

---

## 👤 **Роли пользователей**

<div align="center">
  <table>
    <tr>
      <td align="center" width="200">
        <b>👤 Владелец</b>
      </td>
      <td width="400">
        Полный доступ к управлению своими питомцами, прививками и визитами
      </td>
    </tr>
  </table>
</div>

---

## 🔗 **Полезные ссылки**

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/yourusername/pet-manager">
          <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="40"><br>
          <b>Исходный код</b>
        </a>
      </td>
      <td align="center">
        <a href="https://your-demo-link.com">
          <img src="https://cdn-icons-png.flaticon.com/512/826/826989.png" width="40"><br>
          <b>Демо-версия</b>
        </a>
      </td>
      <td align="center">
        <a href="https://your-api-docs.com">
          <img src="https://cdn-icons-png.flaticon.com/512/2165/2165064.png" width="40"><br>
          <b>API документация</b>
        </a>
      </td>
      <td align="center">
        <a href="https://buymeacoffee.com/yourusername">
          <img src="https://cdn-icons-png.flaticon.com/512/739/739249.png" width="40"><br>
          <b>Поддержать проект</b>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 📅 **Планы развития**

- [x] Базовая система карточек питомцев
- [x] Учёт прививок
- [x] Журнал визитов к ветеринару
- [ ] 🔔 Уведомления о предстоящих прививках (email / Telegram)
- [ ] 📊 Статистика по здоровью питомцев
- [ ] 👥 Поддержка нескольких владельцев для одного питомца
- [ ] 📱 Мобильная версия или PWA
- [ ] 📄 Экспорт данных в PDF
- [ ] 🏥 Интеграция с ветеринарными клиниками

> 🔗 **Следить за обновлениями**: [GitHub Projects](https://github.com/yourusername/pet-manager/projects) | [Changelog](https://github.com/yourusername/pet-manager/releases)

---

## ❓ **Часто задаваемые вопросы**

**В:** Можно ли добавить несколько питомцев?
> *О: Да, вы можете добавить любое количество питомцев.*

**В:** Как получить напоминание о прививке?
> *О: Функция уведомлений находится в разработке. Следите за [новостями](https://t.me/yourchannel)!*

**В:** Будет ли мобильное приложение?
> *О: Планируется в будущих версиях. Голосуйте за эту функцию в [обсуждениях](https://github.com/yourusername/pet-manager/discussions).*

**В:** Можно ли экспортировать данные?
> *О: Функция в разработке. [Подробнее...](https://github.com/yourusername/pet-manager/issues/42)*

---

## 📱 **Социальные сети и контакты**

<div align="center">
  <a href="https://t.me/yourusername">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:email@example.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
  <a href="https://discord.gg/yourserver">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
</div>

---


## 🙏 **Благодарности**

- Всем владельцам домашних животных, которые заботятся о своих питомцах
- Сообществу Django за отличный фреймворк
- Ветеринарам за их нелёгкий труд
- Фотографам за прекрасные снимки животных

---

<div align="center">
  <sub>
    🐾 Сделано с ❤️ для заботливых хозяев | 
    <a href="https://github.com/yourusername/pet-manager/blob/main/LICENSE">MIT License</a> | 
    <a href="https://github.com/yourusername/pet-manager">⭐ Поставить звезду</a>
  </sub>
  <br><br>
  <sub>
    🐕 🐈 🐇 🦜 🐠 🐹
  </sub>
</div>
