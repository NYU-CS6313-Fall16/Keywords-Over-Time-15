# KeywordOverTime
A visualization tool which is used to quickly get the ranking and distribution of some keywords in a dataset.

# Working demo link
[Keyword Over Time](http://www.nemoleoliu.com)

# Vedio demo link
[Keyword Over Time Demo](https://www.youtube.com/watch?v=-0vNBap9--k&feature=youtu.be)


# Guideline for installation
1. The server is based on flask framework. So please make sure you have python and pip in your environment.
2. Install the requirements.(maybe need sudo)
``` 
pip install -r requirements.txt
```
3. Install the mysql database.
4. Create a db called ```kw_db```
5. I'm using 'root' as user and 'root' as password. So if your mysql's account is different from this. Please change line 4 in dataImport.py.
6. Initialize the database.
```
python dataImport.py
```
7. Run the server. (If you just want it to run locally. Please change line 106 '0.0.0.0' to '127.0.0.1:5000')
```
python app.py
```
8. Use browser to access '127.0.0.1:5000'
