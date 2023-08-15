### О курсе
Курс "Python for Data Analysis" погрузит в основы Python и популярные библиотеки для анализа данных NumPy, Pandas, Matplotlib, Seaborn. Курс написан используя инструмент [Jupyter Notebook](https://jupyter.org).\
Курс предназначен для бизнес-экспертов, аналитиков, которые никогда не программировали на Python.\
Содержание курса:
1. Введение в Python
2. Основы NumPy и Pandas
3. Визуализация данных

В каждом блоке присутствуют практические задания и ответы на них.

### Что понадобится для прохождения курса
1. Аккаунт Google. Если у вас есть почта на gmail, то этого будет достаточно

### Инструкция по настройке окружения перед стартом курса
1. Скачать Github репо в формате zip следующим образом:
![](https://rewind.com/wp-content/uploads/2022/03/download_file_gitlab-1536x715.png)
и выбрать расширение zip: ![](https://i.stack.imgur.com/OtFQq.png)
1. Распаковываем zip файл в удобном вам месте, там окажутся 3 папки: **01_Starting_with_Python**, **02_NumPy_and_Pandas**, **03_Data_Visualization**. Это 3 блока курса, внутри папок находятся Jupyter Notebooks, папка Data с данными и Pictures с картинками
2. Далее нам необходимо:
   - зайти на https://www.google.com/drive/
![](https://drive.google.com/uc?id=1ag-W6vs1HsqQIWAuAkZfX-GLZXWYG936)
   - нажать на кнопку "Go to Drive", которую я обвел красным овалом на скриншоте
   - после вас попросят ввести gmail и пароль от него в случае если вы ранее не авторизовывались, вводим и попадаем на главную страницу Google Drive
   - копируем папки из пункта **3**, можно путем drag and drop, на главную вкладки "My Drive" как у меня выделено на скриншоте ниже
    ![](https://drive.google.com/uc?id=1s5FunHbRXSqQKOT1VDFB7mQ2UGapJ68K)
   - теперь нам стоит познакомиться с Google Colab, прежде всего его нужно установить следующим образом:
         - находясь на главной Google Drive кликаем слева верхнем углу **New** -> **More** -> **Connect more apps** -> в поиске вбиваем **Google Colaboratory** и устанавливаем его
         - Следом переходим по ссылке для знакомства с инструментом: https://colab.research.google.com/?hl=ru
   - Как только ознакомились с введением в Google Colab возвращаемся на главную страничку Google Drive и  проваливаемся внутрь папки **01_Starting_with_Python** двойным кликом
   - у первого файла **01_First_steps_in_Python** кликаем на **троеточие**, открывается менюшка там выбираем **Open with** -> **Google Colaboratory** как на скриншоте ниже
   ![](https://drive.google.com/uc?id=1QuMIIRsB7cFbjRyKMPIG5IfYQi9YINMv)
   - Дальше нам откроется Notebook, с этого момента можно начать проходить курс
   ![](https://drive.google.com/uc?id=1k4DaP7jgPm8LqC4n68gcWytmyRIKunuR)
   - И так постепенно проходя каждый Notebook вы пройдете весь курс, каждый блок пронумерован и Notebooks внутри блоков тоже, заблудиться будет сложно :)
1. Иногда вам могут встречаться вот такие ячейки кода:
![](https://drive.google.com/uc?id=194tCUWKEDJ7e9RO-pKs8ju9KkDeBO-8L)
    - их нужно выполнять обязательно, почему спросите вы?
        1. Строчка кода с **drive.mount** синхронизирует ваш Google Colab с Google Drive, что позволяет налету обращаться к данным из той же папки **Data**. В случае если не выполнять, то загрузка данных в ваш Notebook будет вызывать ошибку
        2. Обновляет библиотеки python до новых версий
    - Когда вы будете выполнять ячейку с **drive.mount** Google вас будет спрашивать авторизацию и разрешение на разные действия:
    ![](https://drive.google.com/uc?id=1E8h2Etm-5VEx4lcQPl2sZyQ2Pyx9duDo)
    ![](https://drive.google.com/uc?id=1R0N49K1OkddZm1scdyYcqZ32v3cvYt3-)
      Не переживайте, это нормально, к сожалению, это придется делать каждый раз в каждом Notebook, где вы встретитесь с этой ячейкой кода.
