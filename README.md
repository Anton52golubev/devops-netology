# devops-netology
1) Игнорируем каталог ".terraform" на всех уровнях.
2) Все файлы с расширением .tfstate в любой директории проекта, все файлы, где содержится "tfstate".
3) Файлы журналов сбоев crash.log в любой директории проекта, все файлы, где начинается на "crash." и заканчивается расширением ".log".
4) Все файлы с расширением ".tfvars" и ".tfvars.json" в любой директории проекта.
5) Файлы "override.tf", "override.tf.json" в любой директории проекта. Файлы, в которых содержится название "_override.tf" и "_override.tf.json".
6) Файлы ".terraformrc", "terraform.rc" в любой директории проекта.