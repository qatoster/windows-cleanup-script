# windows-cleanup-script
A simple batch file for quickly clearing unnecessary cache in Windows.   Run it with a double click to delete temporary files and Python bytecode, freeing up space and speeding up your system.

# 🧹 Windows Cleanup Script

Простой бат-файл для очистки кеша в Windows.

## Что делает
- Удаляет временные файлы пользователя и системы (`%TEMP%`, `C:\Windows\Temp`)
- Очищает Корзину (`$Recycle.Bin`)
- Сбрасывает DNS-кеш (`ipconfig /flushdns`)
- Убирает Python-байткод (`*.pyc`, `*.pyo`) и папки `__pycache__`
- Удаляет папки Jupyter `.ipynb_checkpoints`

## Как использовать
1. Скачай [`cleanup.bat`](./cleanup.bat).
2. Запусти двойным кликом (скрипт сам запросит права администратора).
3. Жди сообщение «Готово. Ненужные кеши удалены».

---

⚡ Удобно для программистов и обычных пользователей — быстро освобождает место и устраняет мусор.
