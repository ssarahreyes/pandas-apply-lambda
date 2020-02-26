# Pandas Apply Lambda

The ultimate tool when leading with a [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html) dataframe!!!

![Image](http://www.potacho.com/files/ironhack/pandas.JPG)

---

## **Using the apply function with lambda**
The general syntax is: 

```
df.apply(lambda x: func( x['col1'], x['col2']), axis=1 )
```

> This will allow you to create pretty much any logic, I promise!!! 

### :file_folder: **Data**
To perform the challenges you will use the dataset `/data/imput/IMDB-Movie-Data.csv`

### :panda_face: **Challenge 1. Warm up**
We want to create **bins** of movies according to the number of votes they've received. For that matter, we will create a new column named **'bin'** which will tag every movie as follow:
- From 0 to 1000 ==> 1
- From 1000 to 10000 ==> 2
- From 10000 to 100000 ==> 3
- From 100000 to 1000000 ==> 4
- More than 1000000 ==> 5 

### :panda_face: :panda_face: **Challenge 2. Using axis concept**
...

---

> References:
- [Apply a function to every row in a pandas dataframe](http://jonathansoma.com/lede/foundations/classes/pandas%20columns%20and%20functions/apply-a-function-to-every-row-in-a-pandas-dataframe/)
- [Apply and Lambda usage in pandas](https://towardsdatascience.com/apply-and-lambda-usage-in-pandas-b13a1ea037f7)

