# autoreg_vimeworld

rucaptcha_key - API ключ с сервиса RuCaptcha.

generate_type - Тип генерации ников
- 1: Никнеймы генерируются случайно
- 2: Никнеймы будут одинаковые, но в конце каждого будет увеличиваться цифра

nickname - Ник для аккаунтов. Используется только для 2 типа генерации.
nickname_offset - Начальное значение, которое будет подставляться к строке nickname и увеличиваться на единицу. Используется только для 2 типа генерации.

pass_as_nick
- true: Пароль будет идентичен логину
- false: Пароль будет генерироваться случайно

amount_accounts - Количество аккаунтов.
