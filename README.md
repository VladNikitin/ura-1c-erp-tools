# 1C:ERP Utilities / Утилиты для 1С:ERP

A small collection of external reports and processing utilities for 1C:ERP.

Небольшая коллекция внешних отчётов и обработок для 1С:ERP.

## Downloads / Скачать

Download the `.erf` and `.epf` files from the folders below, or download the ZIP archive from the repository's Releases page when a release is published.

Скачайте файлы `.erf` и `.epf` из папок ниже или ZIP-архив на странице Releases после публикации релиза.

| File / Файл | Purpose / Назначение |
|---|---|
| [`reports/inc&exp_1CERP.erf`](reports/inc%26exp_1CERP.erf) | Income and Expenses report / Отчёт «Доходы и расходы» |
| [`processing/mark_del_1CERP.epf`](processing/mark_del_1CERP.epf) | Marks documents created in a selected period for deletion / Помечает на удаление документы, созданные за указанный период |
| [`processing/del_prod_1CERP.epf`](processing/del_prod_1CERP.epf) | Deletes documents for a selected period / Удаляет документы за указанный период |

**Warning / Внимание:** The two processing utilities may affect or remove business records. **Do not run on production data without authorization, a verified backup and testing in a separate environment.** See [SAFETY.md](docs/SAFETY.md).

**Внимание:** Обработки могут изменять или удалять учетные данные. **Не запускайте в рабочей базе без разрешения, проверенной резервной копии и тестирования в отдельной среде.** Подробности: [SAFETY.md](docs/SAFETY.md).

## Compatibility / Совместимость

Specific 1C:ERP platform and configuration versions have **not yet been confirmed** by the author. Test in a non-production environment before use.

Точные версии платформы и конфигурации 1С:ERP **пока не подтверждены автором**. Сначала проверьте работу в тестовой базе.

## Maintainer and authorship / Авторство и сопровождение

Code author: **Ткаченко Юрий** ([tka777@yandex.ru](mailto:tka777@yandex.ru)).

Repository administrator: **VladNikitin**.

Автор кода: **Ткаченко Юрий** ([tka777@yandex.ru](mailto:tka777@yandex.ru)).

Администратор репозитория: **VladNikitin**.

## License / Лицензия

No open-source license has yet been selected. Public visibility does not itself grant permission to modify or redistribute these files. The code owner should choose a license before public release.

Лицензия пока не выбрана. Публичный доступ сам по себе не даёт разрешения на изменение и распространение файлов. Перед выпуском правообладателю следует выбрать лицензию.
