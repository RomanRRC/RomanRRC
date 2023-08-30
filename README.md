### Bash 👋

Задание № 1 
<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>№</th><th>Команда</th><th>Описание</th></tr></thead><tbody>
 <tr><td>1</td><td>~ </td><td>Открыть домашнюю директорию</td></tr>
 <tr><td>2</td><td>pwd</td><td>Определить имя папки, в которой вы находитесь</td></tr>
 <tr><td>3</td><td>mkdir test1</td><td>Создать внутри этой папки каталог  с именем test1</td></tr>
 <tr><td>4</td><td>cd test1</td><td>Перейти в папку test1</td></tr>
 <tr><td>5</td><td>touch file{1,2,3}.txt</td><td>Создать файл 1,2 и 3 внутри каталога test1</td></tr>
 <tr><td>6</td><td>ls</td><td>Проверить содержимое каталога test1</td></tr>
 <tr><td>7</td><td>cd</td><td>Перейти в домашнюю директорию</td></tr>
 <tr><td>8</td><td>mkdir test2 </td><td>Создать папку test2 внутри домашней директории</td></tr>
 <tr><td>9</td><td>rmdir test2</td><td>Удалить папку test2</td></tr>
 <tr><td>10</td><td>cd test1</td><td>Перейти в папку test1</td></tr>
 <tr><td>11</td><td>rm file2.txt</td><td>Удалить файл 2 из папки test1</td></tr>
 <tr><td>12</td><td>mkdir test3</td><td>Создать папку в домашней директории test3</td></tr>
 <tr><td>13</td><td>touch file{4,5}.txt</td><td>добавить в папку test3 два файла</td></tr>
 <tr><td>14</td><td>cd ..</td><td>Вернуться обратно в каталог</td></tr>
 <tr><td>15</td><td>rm -rf test3</td><td>Удалить папку test3</td></tr>
 <tr><td>16</td><td>ls</td><td>Убедиться, что каталог удален</td></tr>
 <tr><td>17</td><td>mkdir test4</td><td>Создать папку test4 в домашней директории</td></tr>
 <tr><td>18</td><td>mv test1/file{1,3}.txt test4</td><td>Переместить файлы 1 и 3 из папки test1 в папку test4</td></tr>
 <tr><td>19</td><td>echo line11 >> file1.txt</td><td> Добавить в файл 1 три строки со словами line</td></tr>
 <tr><td>20</td><td>echo line12 >> file1.txt            </td><td>&nbsp;</td></tr>
 <tr><td>21</td><td>echo line13 >> file1.txt</td><td>&nbsp;</td></tr>
 <tr><td>22</td><td>cat file1.txt</td><td>Посмотреть содержимое файла 1</td></tr>
 <tr><td>23</td><td>echo line31 >> file3.txt</td><td>Добавить в файл 3 три строки со словами line</td></tr>
 <tr><td>24</td><td>echo line32 >> file3.txt</td><td>&nbsp;</td></tr>
 <tr><td>25</td><td>echo line33 >> file3.txt</td><td>&nbsp;</td></tr>
 <tr><td>26</td><td>cat file1.txt file3.txt</td><td>Просмотреть содержимое двух файлов (1 и 3) сразу</td></tr>
 <tr><td>27</td><td>nano file1.txt + manual replacement</td><td>Используя один из редакторов замените все строки в файле 1</td></tr>
</tbody></table>

Задание № 2

<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>№</th><th>Команда</th><th>Описание</th></tr></thead><tbody>
 <tr><td>1</td><td>mkdir test3 </td><td>Создать папку test 3</td></tr>
 <tr><td>2</td><td>cd test3  </td><td>Перейти в папку</td></tr>
 <tr><td>3</td><td>touch test3/file {4,5,6}.txt</td><td>Добавить в папку test 3 три файла 4, 5 и 6</td></tr>
 <tr><td>4</td><td>echo row1, row2, row3, row4 > file4.txt</td><td>В каждом файле должно быть по 4 строки row1, row2, row3, row4</td></tr>
 <tr><td>5</td><td>echo row1, row2, row3, row4 > file5.txt</td><td>&nbsp;</td></tr>
 <tr><td>6</td><td>echo row1, row2, row3, row4 > file6.txt</td><td>&nbsp;</td></tr>
 <tr><td>7</td><td>cat file{4,5,6}.txt</td><td>Проверка содержания файлов</td></tr>
 <tr><td>8</td><td>grep "row2" 5.txt</td><td>Найдите строку row2 в файле 5</td></tr>
 <tr><td>9</td><td>grep -R "row"</td><td>Найдите строку row в папке test3</td></tr>
 <tr><td>10</td><td>grep -c "row" file6.txt</td><td>Посчитать сколько строк с содержимым row в файле 6</td></tr>
 <tr><td>11</td><td>find 5.txt</td><td>Найдите файл 5 внутри папки test3</td></tr>
 <tr><td>12</td><td>find . -name "file5.txt" -delete</td><td>Используя команду find, удалите файл 5</td></tr>
 <tr><td>13</td><td>echo test >> file4.txt</td><td>Используя команду echo, добавьте слово test в файл 4</td></tr>
 <tr><td>14</td><td>sed 's/test/fail/g' test3/file4.txt</td><td>Замените слово test в файле 4 на fail</td></tr>
 <tr><td>15</td><td>echo test >> test3/file4.txt</td><td>Добавьте в файл 4 слово test так, чтобы сохранилось содержимое</td></tr>
 <tr><td>16</td><td>ps aux</td><td>Просмотрите все процессы для юзеров не только в консоли, которые происходят в системе</td></tr>
 <tr><td>17</td><td>kill 666</td><td>Убейте процесс 666 в консоли</td></tr>
 <tr><td>18</td><td>ping artsiomrusau.com</td><td>Узнайте доступность ресурса artsiomrusau.com, используя ping</td></tr>
 <tr><td>19</td><td>ping -n 5 artsiomrusau.com</td><td>Отправьте 5 пакетов на сайт artsiomrusau.com</td></tr>
 <tr><td>20</td><td>curl -X 'GET' \
  'https://petstore.swagger.io/v2/pet/112' \
  -H 'accept: application/json'
                                                        </td><td>Используя GET и команду curl, получите информацию о зарегистрированных питомцах на https://petstore.swagger.io/</td></tr>
<tr><td>21</td><td>curl -X 'POST' \
  'https://petstore.swagger.io/v2/pet' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "id":112,
  "category": {
    "id": 0,
    "name": "string"
  },
  "name": "doggie",
  "photoUrls": [
    "string"
  ],
  "tags": [
    {
      "id": 0,
      "name": "string"
    }
  ],
  "status": "available"
}'
                                                        </td><td>Используя POST и команду curl, создайте нового пользователя на https://petstore.swagger.io/</td></tr>



</tbody></table>




<!--
**RomanRRC/RomanRRC** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
