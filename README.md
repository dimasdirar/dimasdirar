- I’m love game minecraft, PABG and WoT blits
- 👀 I’m interested in ...@dp.message(Command("start"))
async def cmd_start(message: types.Message):
    kb = [
        [
            types.KeyboardButton(text="/start"),
            types.KeyboardButton(text="/joke"),
            types.KeyboardButton(text="/news_NSK"),
            types.KeyboardButton(text="/smotre"),
            types.KeyboardButton(text="/watch_pubg")
        ],
    ]
    keyboard = types.ReplyKeyboardMarkup(
        keyboard=kb,
        resize_keyboard=True,
        input_field_placeholder="Выберите способ подачи"
        )
    await message.answer("")
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
dimasdirar/dimasdirar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
