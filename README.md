# CRM Система

## Обзор
CRM Система - это веб-приложение на основе React, предназначенное для управления и отслеживания задач и дизайнеров. Приложение оснащено такими функциями, как управление задачами, рейтинг дизайнеров и поддержка нескольких языков. Оно построено с использованием современных технологий, таких как React, Redux, React Router, Material-UI, i18next для интернационализации, axios для запросов к API и Recharts для визуализации данных.

## Технологии
- React: библиотека для построения пользовательских интерфейсов.
- TypeScript: библиотека для типизации кода.
- Redux: управление состоянием приложения.
- React Router: маршрутизация в приложении.
- Material-UI: стилизация и компоненты пользовательского интерфейса.
- i18next: интернационализация и локализация.
- axios: HTTP-клиент для выполнения запросов к API.
- Recharts: библиотека для создания графиков и диаграмм.
- date-fns: библиотека для работы с датами.

## Функциональность
### Главная страница
- Последние комментарии:

  Отображает список последних комментариев с возможностью раскрытия длинных сообщений.
  Комментарии содержат информацию о пользователе, времени создания, связанной задаче и самом сообщении.  

- Топ-10 дизайнеров

  Отображает список из 10 лучших дизайнеров, отсортированных на основе медианного времени выполнения задач и количества выполненных задач.
  Для каждого дизайнера отображается аватар, имя пользователя, медианное время выполнения задач и количество выполненных задач.

### Страница задач
  В этом компоненте мемоизированы тяжелые вычисления задач.

- Линейный график

  Отображает задачи по неделям, включая прибыль, расходы и чистую прибыль.
  Позволяет выбирать количество недель для отображения (4, 8, 12 или 16).

- Круговая диаграмма:
  
  Отображает распределение статусов задач.
  Подписи диаграммы локализованы в соответствии с выбранным языком.


### Страница дизайнеров
- Таблица дизайнеров
- 
  Отображает список дизайнеров с возможностью сортировки и пагинации.
  Содержит колонки с аватаром, именем пользователя, электронной почтой, количеством закрытых задач и количеством задач в процессе.
  Таблица обновляется при переключении страниц или изменения количества строк на странице.


## Установка

1. Клонируйте репозиторий
```
  git clone https://github.com/your-repo/crm-system.git
```
2. Установите зависимости
```
  npm install
```
3. Запустите приложение
```
  npm run dev
```