## Google Python Class Exercise

Google Python Class Exercise: [Baby Names Exercise](https://developers.google.com/edu/python/exercises/baby-names)

#### Things I learned along the way
##### RE
- Basically you use `re.search()` and `re.findall()` to search through a string to find the pattern you need.
- You can use `re.sub(patt,replacement,str)` to replace a pattern
- To extract the pattern from your search, you can write
  ``` python

  ```

##### OS
- Write a list to a file:
  ``` python
  #'a' for append, 'w' for (over)write
  with open('filepath','a') as f:
    f.write('\n'.join(list)
  f.close()
  ```
- Check if a file exists:`os.path.exists(path)`
- Remove a file:  `os.remove(path)`

#### Things I learned comparing my code with the solution(also appear in comment in .py file)
##### When naming variables:
##### 