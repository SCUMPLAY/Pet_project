# ⚽ Итоговая работа Силантьев Сергей по Проекту 1: Футбольные матчи  
## 📌 Юнит 3. Введение в машинное обучение | SkillFactory  
![Python 3.7.4](https://img.shields.io/badge/Python-3.7.4-blue)  

## 📖 Оглавление  
📌 [Описание модуля](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Описание-модуля)  
⚽ [Какой кейс решаем?](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Какой-кейс-решаем?)  
📊 [Краткая информация о данных](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Краткая-информация-о-данных)  
📑 [Полное описание задания с Zindi](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Полное-описание-задания-с-kaggle)  
📓 [Шаблон ноутбука с параметрами модели](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Шаблон-ноутбука-с-параметрами-модели)  
🛠️ [Краткое описание проделанной работы](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Краткое-описание-проделанной-работы)  
🏆 [Результаты](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Результат)  

---  

## 📌 Описание модуля  
📍 Что вы получите в результате работы?  
✔️ Создадите свою первую модель, основанную на алгоритмах машинного обучения.  
✔️ Примете участие в соревновании на Zindi.  
✔️ Узнаете, как правильно "готовить" данные, чтобы улучшить работу модели.  

---  

## ⚽ Какой кейс решаем?  
Футбол — это не просто спорт, а страсть миллионов людей по всему миру. Мы постараемся научиться предсказывать исходы матчей, используя данные о действиях игроков! 🔥  

---  

## 📊 Краткая информация о данных  
📅 Данные собирались **3 года** после **23 команд**.  
🔒 Имена игроков и команд скрыты.  
📂 Датасет доступен в папке [Data](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/Data).  

---  

## 📑 Полное описание задания с Zindi  
📌 Данные включают удары, передачи, ведение мяча и другие игровые события.  
🎯 Цель: **Предсказать исход футбольного матча**.  
🏆 Условия соревнования:  
- Все участники используют **один алгоритм** с фиксированными параметрами.  
- Разрешено использование **внешних данных**.  
- Проверка решений преподавателями на **адекватность и воспроизводимость**.  
📓 Базовое решение доступно во вкладке Notebooks.  

---  

## 📓 Шаблон ноутбука с параметрами модели  
Базовое решение (`Baseline`) использует `LGBMClassifier`:  
```python  
model = LGBMClassifier(n_estimators=1000, random_state=RAND, objective='multiclass')  
```  
📁 Полный ноутбук доступен [здесь](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/Notebooks).  

---  

## 🛠️ Краткое описание проделанной работы  
1️⃣ **Импорт библиотек и данных** 📥  
2️⃣ **EDA Анализ** 🔍  
   - Просмотр общей информации  
   - Визуализация данных  
   - Анализ целевой переменной  
   - Генерация новых признаков  
   - Проверка и обработка пропусков  
3️⃣ **Feature Engineering** 🛠️  
   - Добавление новых статистик  
   - Объединение данных  
   - Кодирование категориальных переменных  
4️⃣ **Моделирование** 🤖  
   - Logistic Regression  
   - XGBoost  
   - RandomForest  
   - LGBM  
   - CatBoost  
5️⃣ **Тюнинг моделей** ⚙️  
   - Поиск гиперпараметров  
6️⃣ **Анализ важных признаков (SHAP)** 📊  
7️⃣ **Stacking лучших моделей** 🎯  
   - Logistic Regression  
   - RandomForest  
   - LGBM  

---  

## 🏆 Результаты  
📉 **Score (LogLoss):** `0.532`  
🥇 **10 место на Zindi** среди `158 участников` (Топ-10%)  
🎖 **Общая оценка:** `94/100`  
💯 **Оценка курса:** `90/100`  
📌 **Детали оценки:**  
✔️ PEP-8: `75/100`  
✔️ Визуализация данных: `100/100`  
✔️ Feature Engineering: `100/100`  
✔️ Работа с метрикой LogLoss: `100/100`  

⬆️ [К оглавлению](https://github.com/SCUMPLAY/Pet_project/blob/main/module_1/README.md#Оглавление)

 
