# Alximik-Stonehearth-Mods

Український переклад для Stonehearth та підтримуваних модів.

## Структура

- `Ukrainian-Translation/manifest.json` — маніфест мода.
- `Ukrainian-Translation/translations/` — переклади `uk.json`.
- `Ukrainian-Translation/ui/` — UI overrides, шрифти, стилі (`mixins.less`).

## Публікація

- Папка `Ukrainian-Translation/Data/` не потрібна для публікації.
- У `.gitignore` додано правило:
  - `/Ukrainian-Translation/Data/`
- Для релізу збирай тільки актуальні файли з `Ukrainian-Translation/`.

## Встановлення

1. Скопіюй папку `Ukrainian-Translation` у директорію `mods` гри Stonehearth.
2. Увімкни мод у менеджері модів.
3. У грі обери українську мову в налаштуваннях.

## Ліцензія

- Основний вміст репозиторію: GNU GPL v3.0 або новіша (див. `LICENSE`).
- Сторонні шрифти мають власні ліцензії:
  - `Ukrainian-Translation/ui/fonts/autourone-uk/SIL OFL Font License Autour One.txt`
