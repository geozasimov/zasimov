# Настройка доступа по SSH
## Откройте терминал и сгенерируйте ключи SSH:
### ssh-keygen -t ed25519 -C "email@phyistech.edu"

### (Лучше не использовать пароль при генерации ключей.)

## Добавляем ключ в ssh-agent:
### ssh-add ~/.ssh/id_ed25519

## Добавляем SSH ключ в аккаунт GitHub.

## Проверяем конект GitHib по SSH
### ssh -T git@github.com

## Для клонирования используем команду:

### git clone "ссылка_в_сибирь.git"
