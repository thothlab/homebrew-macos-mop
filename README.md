# Homebrew tap для mop

[English](README.en.md) | **Русский**

Официальный [Homebrew](https://brew.sh) tap для утилиты [mop](https://github.com/thothlab/macos-mop) — быстрого CLI-инструмента для очистки macOS.

## Установка

```bash
brew tap thothlab/macos-mop
brew install mop
```

## Использование

```bash
# Показать что можно очистить (без удаления)
mop clean --dry-run --all

# Очистить всё
mop clean --all

# Полное удаление приложения со всеми файлами
mop uninstall "Slack"

# Анализ дискового пространства
mop analyze ~/Documents

# Удалить сборочные артефакты (node_modules, target, .build...)
mop purge ~/Projects

# Состояние системы
mop status
```

## Обновление

```bash
brew update
brew upgrade mop
```

## Удаление

```bash
brew uninstall mop
brew untap thothlab/macos-mop
```

## Ссылки

- [Исходный код](https://github.com/thothlab/macos-mop)
- [Релизы](https://github.com/thothlab/macos-mop/releases)
- [Сообщить о проблеме](https://github.com/thothlab/macos-mop/issues)

## Лицензия

MIT
