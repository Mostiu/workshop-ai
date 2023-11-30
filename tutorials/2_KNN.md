#  K Nearest Neighbours (kNN)

## Cel
Celem tego zadanie jest przygotowanie kodu, który wykona zadanie klasyfikacji binarnej za pomocą algorytmu k najbliższych sąsiadów. kNN jest modelem prostym, dlatego bardziej należy się skupić na wykonaniu poprawnie pipelinu danych oraz dogłębnym zrozumieniu stosowanych metod.

## Pipeline

### Podział na zbiór testowy i treningowy
Najważniejszy etap, zawsze wykonywany na początku pracy z danymi. \
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

### Preprocessing danych
Należy pamiętać, że wszystkie metody powinny być fit'owane na zbiorze treningowym, a zbiór testowy powinien być tylko przez nie transformowany. \
https://scikit-learn.org/stable/modules/preprocessing.html

### Wyuczenie modelu i obliczenie miar
Wyuczenie modelu kNN na zbiorze treningowym oraz sprawdzenie jego dokładności na zbiorze testowym. \
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html \
https://www.youtube.com/watch?v=HVXime0nQeI \
https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/ \
https://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics