# Предсказание оттока пользователей

Данный учебный проект был выполнен в рамках курсов DLS при ФПМИ МФТИ

Проект посвящен моделированию оттока клиентов телеком-компании. 
### Почему это важно?
Если мы знаем, что клиент собирается покинуть компанию, то можно попытаться удержать его, предложив ему бонусы или скидки, или исправить ситуацию так, чтобы другой похожий клиент не ушел от нас в дальнейшем.

### Информации о проекте
Данный проект выполнялся осенью 2024 года в рамках курсов DLS (Школа глубокого обучения ФПМИ МФТИ).
Использовался Python + scikit-learn + catboost

Файлы проекта:
- [test.csv](https://github.com/AgapovKS/pet_projects/blob/main/project_01_ml_boosting/train.csv): Датасет используемый для обучения модели
- [test.csv](https://github.com/AgapovKS/pet_projects/blob/main/project_01_ml_boosting/train.csv): Датасет используемый для тестирования модели
- [best_catboost_model.cbm](https://github.com/AgapovKS/pet_projects/blob/main/project_01_ml_boosting/best_catboost_model.cbm): Модель, обученная с помощью catboost
- [my_submission.csv](https://github.com/AgapovKS/pet_projects/blob/main/project_01_ml_boosting/my_submission.csv): Сабмит, направляемый в Kaggle

### Результаты
Получилось достигнуть: ROC-AUC: 0.8474 на обученной модели.
А на Kaggle результат достиг 0.85268
