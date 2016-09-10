# slack-vk-bot 
[![build status](https://gitlab.com/murych/slack-vk-bot/badges/master/build.svg)](https://gitlab.com/murych/slack-vk-bot/commits/master)

## самоцель
бот, связанный с __VK Callback API__, ловящий информацию о событии `new_wall_post` и сообщающий об этом в чат __Slack__

## настройка переменных окружения

| переменная           | описание                                                                       |
|----------------------|--------------------------------------------------------------------------------|
| `TEXT`               | текст, выводящийся перед `attachment`                                          |
| `CHANNEL`            | канал, в который бот отправляет сообщения                                      |
| `SLACK_BOT_SECRET`   | секретный ключ, доступный при [создании бота](https://api.slack.com/bot-users) |
| `CONFIRMATION_TOKEN` | токен __VK callback API__ доступный в настройках сообщества                    |

## планы на будущее
- поддержка бОльшего количества событий
- прикрепление фотографий к посту
- осознание того, что бот сообщает о репосте