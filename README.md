## Используемые обозначения

- Все команды начинаются или с `/`, или с `.`
- `/команда <аргумент>` Здесь внутри `<>` приводится название/описание аргумента. На месте `<аргумент>` надо написать то, что требует данная команда
- `/команда <?аргумент?>` Здесь говорится, что `<?аргумент?>` является не обязательным
- Сами угловые скобки `<>` писать не надо. Только то, что внутри
- `👤` — id или ответ на сообщение пользователя с которым надо выполнить какие-то действия
- `👥` — Можно указать нескольких пользователей сразу
- `💰` — Команду можно использовать только за монетки

## Общие команды
- `/help` или `/commands` Получить ссылку на эту страницу
- `/start` Зарегистрировать чат и администраторов, нужно написать после добавления бота в чат
- `/version` Версия бота
- `/profile 👤` Посмотреть профиль пользователя
- `/balance 👤` Посмотреть баланс пользователя

## Роли

Управление ролями:

- `/roles` Показать список ролей чата
- `/staff <?уровень прав?>` Показать всех обладателей каждой из ролей
- `/addrole <название роли> <уровень прав>` Создать новую роль
- `/delrole <название роли>` Удалить роль. Все пользователи будут разжалованы, которые имели данную роль

Модератор команды:
- `/moder <роль> 👤` Выдать указанную роль пользователю
- `/resign` Снять с себя роль (админы, осторожно!)
- `/recover` Восстановить свою роль. Восстановит роль исходя из того, кем вы являетесь в чате
- `/ban 👤` Забанить пользователя
- `/warn 👤` Выдать предупреждение
- `/warns` Посмотреть предупреждения чата


## Настройка чата

- `/settings` - посмотреть настройки чата
- `/dk <название команды> <уровень прав>` Изменить доступ к команде

## Развлекательные команды
Основные игры:
- 💰 `/casino <ставка>` Сыграть в игрe «казино»
- 💰 `/hunting <ставка>` Сыграть в игру «охота»

Передача игровой валюты:
- 💰 `/give <количество монеток> 👤` Передать `<количество монеток>` пользователю

Команды связанные с аниме:
- 💰 `/waifu` Кинет рандомную фотку вайфы за 5 монеток
- 💰 `/megumin` Кинет рандомную фотку мегумин за 5 монеток
- `/anime <название аниме>` Поиск аниме по названию

## Бонусы
- `/bonus` Получить бонус. Можно использовать раз в 12 часов

Чтобы активировать промокод, напишите его в лс [боту](t.me/yabada_bot). А вот и промокод! `yabada_cmd`

## Вип

Посмотреть информацию об випе:
- `мой вип` Напишет когда закончится вип или сообщит как можно его получить

Что дает вип?
- Бонус в размере ×2

## Реферальная система
Чтобы получить ссылку на реферальную ссылку, отправьте боту: `/referer`
Отправьте её вашим друзьям. Если Ваш друг перейдет по ссылке и он не был чьим-то рефералом, то вы получите +1 день випа, а друг +100💰 на свой баланс!

## Версия
Документация написана для версии бота: `0.2.1`
Чтобы узнать версию бота, пишите: `/version`
