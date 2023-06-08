### **Команды для Git Hub**


**git clone [https://name_code_3.git](https://адрес_файла/.git)**   копирует код с Git Hub

**cd name_file**     меняет директорию на указанное имя файла (change directory)

**git push**    публикует изменения в локальном репозитории в интернет

**git pull**      синхронизирует версии на локальном и удаленном репозитории


### **Создать репозиторий прямо в Git**

echo "# Test" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Snussmumrik/Test.gitgit push -u origin main

### **Залить локальный репозиторий в Git**

git remote add origin https://github.com/Snussmumrik/Test.git

git branch -M main

git push -u origin main