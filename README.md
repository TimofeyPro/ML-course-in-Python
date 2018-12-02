### Python implementations of the exercises presented by Andrew Ng in "Machine Learning" class on Coursera.  
You may find more details in Russian at [timofey.pro](https://timofey.pro/AI/Ng.html)  
 

#### [Exercise 4: Neural Networks Learning](Exercise4_Neural_Networks_Learning)

1. How to check the current working directory? Как узнать текущую рабочую директорию? [checkWD.ipynb](Exercise4_Neural_Networks_Learning/checkWD.ipynb)  
2. How to change (set) the current working directory? Как изменить рабочую директорию? [checkWD.ipynb](Exercise4_Neural_Networks_Learning/checkWD.ipynb)
3. How to upload .mat file into Python and see its structure | Как загрузить .mat файл в Python и посмотреть его структуру? [ex4.ipynb](Exercise4_Neural_Networks_Learning/ex4.ipynb)
4. Using [one-hot encoding ](https://www.quora.com/What-is-one-hot-encoding-and-when-is-it-used-in-data-science) for  "y" array transformation | Использование [one-hot encoding ](https://www.quora.com/What-is-one-hot-encoding-and-when-is-it-used-in-data-science) для преобразования массива "y". [One hot encoding](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html) преобразует категориальные признаки (features) в формат, который лучше работает с алгоритмами классификации и регрессии.  
5. **Visualizing the data | Визуализация данных**  
        5.1 ```_, axarr = plt.subplots(10,10,figsize=(12,12))``` - Subplotting is a technique for creating multiple plots that live side-by-side in one overall figure. Subplots takes two arguments. The first one controls the number of rows, the second one the number of columns.  
        5.2 ```np.random.randint(X.shape[0])```- Return random integer from [0, 5000) | Вернет одно целое число из [0, 5000)  
        5.3 **plt.imshow()** function interprets a two-dimensional grid of data as an image. Suggested reading - Chapter 4. Visualization with Matplotlib. Python Data Science Handbook by Jake VanderPlas. 
        
        
        
        
        
You can find useful links to other solutions [here](https://github.com/jdwittenauer/ipython-notebooks), [here](https://github.com/kaleko/CourseraML/blob/master/ex4/ex4.ipynb), [here](https://medium.com/analytics-vidhya/a-guide-to-using-logistic-regression-for-digit-recognition-with-python-codes-86aae6da10fe) and [here](https://github.com/andrewenoble/machine-learning-andrew-ng).
