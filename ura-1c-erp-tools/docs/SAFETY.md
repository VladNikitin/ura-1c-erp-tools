# Safety / Безопасность

## English

- `mark_del_1CERP.epf` is described as marking documents created within a selected time period for deletion.
- `del_prod_1CERP.epf` is described as deleting documents within a selected time period.
- These descriptions were supplied by the author/requester; the embedded code has **not** been independently inspected or tested.
- Only authorized administrators should use these processing utilities.
- Before execution: verify the intended database, document types, date boundaries and inclusivity, permissions, dependencies, and the ability to restore from a backup.
- Test on a separate copy of the database first. Verify a complete backup and practice restoration.
- Review the code and behavior for effects on accounting records, references, and audit trails. Consider legal or regulatory record-retention requirements.
- No warranty or safety certification is provided.

## Русский

- `mark_del_1CERP.epf` — по описанию, помечает на удаление документы, созданные за выбранный период.
- `del_prod_1CERP.epf` — по описанию, удаляет документы за выбранный период.
- Описания предоставлены автором/пользователем; встроенный код **не проходил независимую проверку или тестирование**.
- Применять обработки должны только уполномоченные администраторы.
- Перед запуском проверьте базу, типы документов, границы периода, права, зависимости и возможность восстановления.
- Сначала проверьте на отдельной копии базы. Создайте и проверьте резервную копию; убедитесь, что восстановление работает.
- Проверьте влияние на бухгалтерские данные, связи документов и журналы регистрации. Учитывайте требования к хранению документов.
- Гарантии и сертификаты безопасности не предоставляются.
