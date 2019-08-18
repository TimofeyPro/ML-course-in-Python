### Python implementations of the exercises presented by Andrew Ng in "Machine Learning" class on Coursera.  
You may find more details in Russian at [timofey.pro](https://timofey.pro/AI/Ng.html)  

#### [Exercise 1: Linear Regression with One Variable](https://github.com/TimofeyPro/ML-course-in-Python/tree/master/Exercise1:%20Linear%20Regression)

   1. [Ex1: Solution using Pandas and Numpy](https://github.com/TimofeyPro/ML-course-in-Python/blob/master/Exercise1:%20Linear%20Regression/ex1-v02.ipynb)
   2. [Ex1: Solution using scikit-learn](https://github.com/TimofeyPro/ML-course-in-Python/tree/master/Exercise2:%20Linear%20Regression%20with%20multiple%20variables)


#### [Exercise2: Linear Regression with multiple variables](https://github.com/TimofeyPro/ML-course-in-Python/tree/master/Exercise1:%20Linear%20Regression)


#### [Exercise 4: Neural Networks Learning](Exercise4_Neural_Networks_Learning)

1. How to check the current working directory? Как узнать текущую рабочую директорию? [checkWD.ipynb](Exercise4_Neural_Networks_Learning/checkWD.ipynb)  
2. How to change (set) the current working directory? Как изменить рабочую директорию? [checkWD.ipynb](Exercise4_Neural_Networks_Learning/checkWD.ipynb)
3. How to upload .mat file into Python and see its structure | Как загрузить .mat файл в Python и посмотреть его структуру? [ex4.ipynb](Exercise4_Neural_Networks_Learning/ex4.ipynb)
4. Using [one-hot encoding ](https://www.quora.com/What-is-one-hot-encoding-and-when-is-it-used-in-data-science) for  "y" array transformation | Использование [one-hot encoding ](https://www.quora.com/What-is-one-hot-encoding-and-when-is-it-used-in-data-science) для преобразования массива "y". [One hot encoding](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html) преобразует категориальные признаки (features) в формат, который лучше работает с алгоритмами классификации и регрессии.  
5. **Visualizing the data | Визуализация данных**  
        5.1 ```_, axarr = plt.subplots(10,10,figsize=(12,12))``` - Subplotting is a technique for creating multiple plots that live side-by-side in one overall figure. Subplots takes two arguments. The first one controls the number of rows, the second one the number of columns.  
        5.2 ```np.random.randint(X.shape[0])```- Return random integer from [0, 5000) | Вернет одно целое число из [0, 5000)  
        5.3 **plt.imshow()** function interprets a two-dimensional grid of data as an image. Suggested reading - Chapter 4. Visualization with Matplotlib. Python Data Science Handbook by Jake VanderPlas [Link](https://www.oreilly.com/library/view/python-data-science/9781491912126/ch04.html).  
6. [Manual](https://docs.scipy.org/doc/numpy/reference/generated/numpy.insert.html) for numpy.insert(arr, obj, values, axis=None) function.  
7. [Manual](https://docs.scipy.org/doc/numpy/reference/generated/numpy.ones.html) for numpy.ones(shape, dtype=None, order='C') function.  
8. [Manual](https://docs.scipy.org/doc/numpy/reference/generated/numpy.matrix.html) for numpy.matrix(data, dtype=None, copy=True) function.  
9. [Manual](https://docs.scipy.org/doc/scipy-0.15.1/reference/generated/scipy.optimize.minimize.html) for scipy.optimize.minimize(fun, x0, args=(), method=None, jac=None, hess=None, hessp=None, bounds=None, constraints=(), tol=None, callback=None, options=None) function.  
        
  #### [Exercise 5:](Exercise4_Neural_Networks_Learning)      
        
  Coming soon
  
You can find useful links to other solutions [here](https://github.com/jdwittenauer/ipython-notebooks), [here](https://github.com/kaleko/CourseraML/blob/master/ex4/ex4.ipynb), [here](https://medium.com/analytics-vidhya/a-guide-to-using-logistic-regression-for-digit-recognition-with-python-codes-86aae6da10fe) and [here](https://github.com/andrewenoble/machine-learning-andrew-ng).
