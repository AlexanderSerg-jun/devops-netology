# devops-netology
### My first repository 
### В файле .gitignore, которая находится в папке terraform , описаны файлы которые будут игнорировать при загрузке  в репозиторий
# Локальные каталоги .terraform
.terraform/

# Любые файлы .tfstate
*.tfstate
*.tfstate.*

# журнала сбоев crash.log
crash.log
crash.*.log

# Файлы содержащие секретные данные 
*.tfvars
*.tfvars.json

# Игнорируйте файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов и, следовательно,не проверяются
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Игнорирование информации о временной блокировке, созданные terraform
.terraform.tfstate.lock.info


# Игнорирование CLI конфигурационных файлов
.terraformrc
terraform.rc