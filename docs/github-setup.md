# Настройка GitHub

Рекомендуемые настройки GitHub для `yeoman-feedback`.

## Метки

Базовый набор labels:

- `bug`:
  ошибка или некорректное поведение.
- `feedback`:
  общий пользовательский или командный фидбек.
- `enhancement`:
  предложение по улучшению.
- `documentation`:
  правки или замечания по документации.
- `needs-info`:
  не хватает деталей для разбора.
- `confirmed`:
  проблема или запрос подтверждены.
- `planned`:
  принято в работу.
- `duplicate`:
  дубликат существующего issue.
- `question`:
  вопрос без явного баг-репорта или change request.
- `good first issue`:
  подходящая задача для первого вклада.
- `help wanted`:
  нужен внешний вклад или помощь в проработке.

## Рекомендуемые цвета

Если нужен единый визуальный стиль, можно использовать такие цвета:

- `bug` -> `d73a4a`
- `feedback` -> `1d76db`
- `enhancement` -> `a2eeef`
- `documentation` -> `0075ca`
- `needs-info` -> `fbca04`
- `confirmed` -> `0e8a16`
- `planned` -> `5319e7`
- `duplicate` -> `cfd3d7`
- `question` -> `d876e3`
- `good first issue` -> `7057ff`
- `help wanted` -> `008672`

## Правила для веток

Для основной ветки `main` рекомендуется:

1. Запретить прямые push в `main`, если в репозитории будет больше одного участника.
2. Включить `Require a pull request before merging`.
3. Требовать минимум 1 approval, если изменения будут проходить через review.
4. Включить `Dismiss stale pull request approvals when new commits are pushed`.
5. Включить `Require conversation resolution before merging`.
6. Разрешить merge только после прохождения обязательных проверок, если позже появится CI.

## Рекомендуемые настройки репозитория

- Включить issue templates.
- Отключить blank issues.
- Включить squash merge как основной способ merge.
- Опционально отключить merge commit, чтобы история была чище.
- Добавить repository description про сбор обратной связи по Monopoly - yeoman.

## Рекомендуемое описание

`Репозиторий обратной связи для Monopoly - yeoman: баги, продуктовый фидбек, UX-замечания и идеи улучшений.`

## Минимальный стартовый набор меток

Если хочешь начать с минимума, сначала достаточно создать:

- `bug`
- `feedback`
- `enhancement`
- `needs-info`
- `planned`
- `duplicate`
