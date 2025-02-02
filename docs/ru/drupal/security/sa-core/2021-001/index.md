---
title: SA-CORE-2021-001
slug: security/sa-core-2021-001
metatags:
  title: 'Drupal: SA-CORE-2021-001'
  description: 'Критическое. Исправлено в версиях: 8.9.13, 9.0.11, 9.1.3.'
---

**Проект:** Drupal Core\
**Дата публикации:** 20 января 2021\
**Риск безопасности:** Критический. 18/25 AC:Complex A:User CI:All II:All E:Exploit TD:Uncommon\
**Уязвимость:** Сторонние библиотеки.

## Описание

Drupal ядро использует библиотеку PEAR Archive_Tar. Данная библиотека выпустила обновление безопасности которое также влияет на Drupal. Для более подробной информации смотрите:

- [CVE-2020-36193](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-36193)

Возможны уязвимости если Drupal настроен на загрузку и выполнение файлов с расширениями `.tar`, `.tar.gz`, `.bz2 `или `.tlz`.

**Для устранения данной проблемы, убедитесь что возможность загрузки файлов .tar, .tar.gz, .bz2 и .tlz имеется только у доверенных пользователей.**

## Решение

Обновиться до актуальных версий:

- Если используете Drupal 8.9.x, обновитесь до [Drupal 8.9.13](../../../releases/8/8.9.x/8.9.13/index.md).
- Если используете Drupal 9.0.x, обновитесь до [Drupal 9.0.11](../../../releases/9/9.0.x/9.0.11/index.md).
- Если используете Drupal 9.1.x, обновитесь до [Drupal 9.1.3](../../../releases/9/9.1.x/9.1.3/index.md).

## Ссылки

- [SA-CORE-2021-001](https://www.drupal.org/sa-core-2021-001) (англ.), drupal.org, 20 января 2021