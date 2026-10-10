notebook.ipynb выполняет очистку датасета Titanic: загружает данные с Google Drive, 
анализирует пропуски (177 в Age, 687 в Cabin, 2 в Embarked), 
заполняет Age медианой с приведением к int64, Cabin и Embarked — значением «Unknown», 
проверяет дубликаты (их нет), 
переводит Sex и Embarked в категориальный тип для экономии памяти и удобства, после чего сохраняет очищенный датасет в CSV под названием cleaned_Titanic_dataset.csv
