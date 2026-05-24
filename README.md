## Данные об авторе
Екимова Мария Денисовна
ekimova_md_23
3 курс / 6 семестр
Кибербезопасность
Курсовой проект
# Название проекта
Автоматизированный анализ безопасности мобильных приложений на основе сетевого трафика с использованием методов машинного обучения
## Требования
*   Python 3.9+
*   Основные библиотеки
  - pandas
  - numpy
  - scikit-learn
  - xgboost
    Для обучения модели рекомендуется 16+ ГБ оперативной памяти, так как датасет достаточно большой
## Структура проекта
├── main.py                    
├── requirements.txt
├──.gitignore
├── README.md
├── Benign/                    
├── Adware/
├── Ransomware/
├── Scareware/
└── SMSmalware/
## Как запустить
1.  Клонируйте репозиторий:
git clone https://github.com/username/repo.git
cd repo
2. Установите зависимости:
pip install -r requirements.txt
3. Поместите папки с данными (Benign, Adware, Ransomware, Scareware, SMSmalware) в корень проекта
4.  Запустите проект:
python main.py