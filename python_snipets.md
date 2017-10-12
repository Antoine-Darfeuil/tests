# Python Snippets


#### Check if a file exit
```
import os
os.path.isfile(file_name)


try:
    my_abs_path = my_file.resolve():
except FileNotFoundError:
    # doesn't exist
else:
    # exists
    
```

#### Dataframe


#### Pickle

```
import pickle 

with open('filename.pkl', 'wb') as f:
  pickle.dump(object, f)
  
with open('filename.pkl', 'rb') as f:
  X = pickle.load(f)

```
