# devops-netology-Devops-Miheev
### Что игнорируется Terraform .gitignore

- `*.tfstate` — любые файлы с расширением .tfstate
- `*.tfstate.*` — файлы, имя которых начинается с `.tfstate.`
- `.terraform/` — папка .terraform и всё её содержимое
- `crash.log` и `crash.*` — файлы crash-логов
- `*.tfvars` и `*.tfvars.json` — файлы с конфигурациями переменных
