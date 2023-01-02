# игнорирует все файлы в скрытой директории .terraform
**/.terraform/*

# игнорирует файлы с расширением .tfstate и файлы, где в названии есть слово tfstate
*.tfstate
*.tfstate.*

# игнорирует лог файл crash.log и файлы, которые начинаются на crash и имеют расширение log
crash.log
crash.*.log

# игнорирует файлы с расширением .tfvars и .tfvars.json
*.tfvars
*.tfvars.json

# игнорирует файлы override.tf override.tf.json и файлы, имя которых заканчиваются на *_override.tf и *_override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# игнорирует файлы .terraformrc terraform.rc
.terraformrc
terraform.rc
