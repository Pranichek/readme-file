1)тема проекта с какой целью он создавался 
2)как запустить проект(устновка пайтон, установка с гита , создавние вирутального окружения , python main.py)
3)структура requirements описание кажого модуля , с какой целью они используються в проекте
4)схема проекта(figjam or in readme)
5)описание каждого пакета в modules и файлы в нутри пакета(код) , коментарии на англ или на укр 
6)с какой целью каждый файл
7)ссылка на библиотеки где брал информацию
8)какие были проблемы при создании проекта , как решил проблему с которой столкнулся
9)сделать работу над ошибками(потоки , не создавал классы)
10)висновок на укр и на англ(с чем помог проект, как он меня прокачал , чем он был мне полезен)

# Music PLayer
## About project
The main goal of developing this program was to improve skills in working with the customtkinter library and gain experience in creating functional applications with an attractive graphical user interface. 
Naturally, this program was developed to provide a convenient way to play music on your computer.

Additionally, the development of this project helped to better understand how to work with events, customize interface elements, and leverage various libraries to create a unified functional application. 
The result is a music player that can serve as a foundation for further enhancement and adding new features, such as fetching relevant information from external music services.

<details>
<summary>Ukraine version</summary>
Головною метою розробки цієї програми було вдосконалення своїх навичок роботи з бібліотекою customtkinter, 
а також отримання досвіду у створенні функціональних додатків із привабливим графічним інтерфейсом.
Звісно ця програма розроблена для забезпечення зручного  способу відтворення музики на вашому комп'ютері.

Окрім того,розробка цього проєкту допомгла краще зрозуміти, як працювати з подіями, налаштовувати кастомні елементи інтерфейсу, 
а також як можна використовувати різні бібліотеки для створення єдиного функціонального додатку. Результатом став музичний плеєр, 
який можна використовувати як базу для подальшого вдосконалення та додавання нових функцій, 
таких як брати потрібну інформацію із зовнішніх музичних сервісів.
</details>

# Getting Started
Below will be instructions on how you can download this project to your device.

## Installing python
This is an example of how to install python if you never use him
- Download the Python Installer
    - Go to the official [Python website](https://www.python.org)
    - Navigate to the Downloads section. The website automatically detects your operating system and displays the appropriate version.
- Choose the Right Version
    - For most users, the latest stable version is recommended. But if you don't have the latest version, try downloading another one.
- Download the Installer
    - Click on the Download Python button. This button will be in the top right corner of your screen.
- Customize Installation Options 
    - Check the box "Add Python to PATH" at the bottom of the installer window. This step is crucial for running Python from the command line
    - Click Customize installation if you want to select additional options, but the default settings work fine for most users.
- Install python
    - Finnaly you can click the Install Now button and wait for the installation to complete.
- Verify the Installation
    - After installation, open your terminal or command prompt.
        <details>
        <summary> Operating system</summary>
        - On Windows: Press Win + R, type cmd, and press Enter.
        - On macOS/Linux: Open the Terminal application.
        </details>
    - Type ```python --version``` or ```python3 --version``` and press Enter.
    - If Python is installed correctly, you will see the installed version displayed

If you still don't get how to install python, you can watch [here](https://www.youtube.com/watch?v=YKSpANU8jPE)


## Installing this project
1. Clone the project
    - Went to the main page of project on github.
    - Click the green "Code" button located at the top right.
    - Select the HTTPS option and copy the project URL.
2. Open project in an IDE
    - Launch your preferred IDE(Vscode , PyCharm or another one)
    - Open it , and select "Open Folder" option to navigate to and open the directory where the project was cloned.
    - Press Control + J or just create new terminal , and write this:
    ```python
    git clone <repository_url>
    ```
3. Prepare the project for use
    - Go to the main project folder
        ```python  
        cd music_player
        ```
4. Сreate a virtual environment

    For macOS/Linux:

        python3 -m venv venv
    For Windows:

        python -m venv venv
4. Activate the Virtual Environment

    On macOS/Linux:

        source venv\Scripts\activate
    On Windows:

        venv\Scripts\activate
5. Install Project modules
    - Once the virtual environment is active, install the required libraries by running:

        ``` 
        pip install -r requirements.txt 
        ```
6. Launch program
    - For start the Music Player, use the following command:
        ``` python
        python main.py
        ```

# MODULES FOR PROGRAM

### MODULES FOR DOWNLOADING

* customtkinter - To create a music player GUI/Для створення графічного інтерфейсу музикального плеєру
* pygame - Loading and playing music for music_app/Завантаження та програвання музики для додатку
* pillow - For open and process image files before passing them to customtkinter/Для відкриття та обробки файлів зображень перед передачею їх у customtkinter

### BASE MODULES PYTHON

* os - searching absolute path
* threading - Used to create and manage streams so that you can play music continuously without stuttering or errors/Використовується для створення потоків і керування ними, для того щоб можна було безперервно програвати музику без зависань та помилок
* random - Used for the function of playing random music/Використовувся для функції програвання рандомної музики
* json - Used for reading JSON files and images for project/Використовувався для отримання необхідної інформації з JSON файлів, а також для зчитування шляхів до зображень.

# Scheme of the project
```mermaid
graph TD;
    music_player-->modules;
    modules-->modules_init["__init__.py"];
    modules-->frames;
    frames-->frames_init["__init__.py"];
    frames-->buttom_frame.py;
    frames-->frame_for_songs.py;
    frames-->main_frame.py;
    frames-->side_frame.py;
    modules-->load_images;
    load_images-->load_images_init["__init__.py"];
    load_images-->get_images.py;
    modules-->json_functions;
    json_functions-->json_functions_init["__init__.py"];
    json_functions-->read_images.py;
    json_functions-->read_json.py;
    music_player-->static;
    static-->images;
    static-->config.json;
    music_player-->main.py;
    music_player-->README.md;
    music_player-->requirements.txt;
    music_player-->gitignore[".gitignore"];
```










    


        


```
hahahahahahah
```

```python
    print(dfkmfd)
    def ():
        print()
```

<a href="https://fonts.google.com/selection"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/mfts0"></a>

<a >

<!-- start:code block -->
# Clone this repository
git clone https://github.com/Pranichek/Music_player
cd papermark

# Install dependencies
npm install

# Copy the example .env file
cp .env.example .env

# Initialize the database
npx prisma generate
npx prisma db push

# Run the app
npm run dev

# Open https://github.com/Pranichek/Music_player in your browser
open https://github.com/Pranichek/Music_player
<!-- end:code block -->


## Getting started
*This is readme file about my project music player.*


**This is readme file about my project music player.**


***This is readme file about my project music player.***

~~*__This is readme file about my project music player.__*~~

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcAOQOXpz3-LzbrnJJkZnn5jejcz7HPJyAkw&s" alt="alternative_text">

Привет это [обычная ссылка в строке](https://www.google.com)

- Первый 1. Пункт 1.
- Второй 1. Пункт 2.
- Третий 1. Пункт 3.





- [X] Write music player
- [ ] nothing
- [X] add thread





- Уровень списка 1. Пункт 1.
    - Уровень списка 2. Пункт 1.
- Уровень списка 1. Пункт 2.
    - Уровень списка 2. Пункт 1.
    - Уровень списка 2. Пункт 2.
- Уровень списка 1. Пункт 3.
    - Уровень списка 2. Пункт 1.
        - Уровень списка 3. Пункт 1.
        - Уровень списка 3. Пункт 2.
           - Уровень списка 4. Пункт 1.