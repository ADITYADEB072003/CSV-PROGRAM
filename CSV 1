```python
print("HEADER")
import pandas as pd
c=pd.read_csv("file.csv",header=None)
d=pd.DataFrame(c)
print(d)
```

```python
print("NAMES")
import pandas as pd
c=pd.read_csv("file.csv",header=None,names=["name","sub","marks","id"])
d=pd.DataFrame(c)
print(d)
```

```python
print("Skiprows")
import pandas as pd
c=pd.read_csv("file.csv",header=None,names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
print(d)
```

```python
print("index_col")
import pandas as pd
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],index_col="id",skiprows=1)
d=pd.DataFrame(c)
print(d)
```

```python
print("nrows")
import pandas as pd
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],index_col="id",skiprows=1,nrows=3)
d=pd.DataFrame(c)
print(d)
```

## PLOTING IN CSV

```python
import pandas as pd
import matplotlib.pyplot as plt
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
plt.hist(d["id"],bins=40,cumulative=True,histtype="barstacked",orientation="horizontal")
plt.show()
```

```python
import pandas as pd
import matplotlib.pyplot as plt
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
plt.bar(d["id"],d["marks"])
plt.show()
```

```python
import pandas as pd
import matplotlib.pyplot as plt
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
plt.scatter(d["id"],d["marks"])
plt.show()
```

```python
import pandas as pd
import matplotlib.pyplot as plt
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
plt.pie(d["id"],autopct="%0.6f%%")
plt.show()

```

```python
import pandas as pd
import matplotlib.pyplot as plt
c=pd.read_csv("file.csv",names=["name","sub","marks","id"],skiprows=1)
d=pd.DataFrame(c)
plt.boxplot(d["id"],showmeans=True,meanline=True,notch=True)
plt.show()
```
