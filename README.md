**Избранное 📝**

🗑️ `!delete` - удалить все сообщения.  
🖇️ `/текст/` - отправить текст с функцией быстрого копирования.

**Установка:**

```bash
cd public_html
```
```bash
git clone https://github.com/kage-kao/FavouritesSite.git
```
```bash
mv FavouritesSite/.* ./ 2>/dev/null || true
mv FavouritesSite/* ./ 2>/dev/null || true
rm -rf FavouritesSite
```
```bash
chmod 755 uploads && chmod 666 messages.json
```
