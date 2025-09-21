# Masha Repo Template (latest branch support)

Шаблон для подключения Маши с автопубликацией prompt.txt в ветку `prompt/latest`.

## Основные шаги
1. Залей содержимое архива в новый репозиторий GitHub.
2. Запусти workflow (chat_start).
3. Файл `prompt.txt` будет автоматически собран и запушен в ветку `prompt/latest`.
   Ссылка для подключения:
   ```
   https://raw.githubusercontent.com/<OWNER>/<REPO>/prompt/latest/prompt.txt
   ```
4. После чата дерни `chat_end` с обновлённым session_state и заметкой для growth_journal.

