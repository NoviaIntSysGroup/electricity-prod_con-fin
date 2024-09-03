# Instructions to Download
```python
import gdown
import zipfile
import os
url = 'https://drive.google.com/uc?id=1VN9CGn1dDQL6nCWFWkGL49voxQfY8Dqt'
output = 'jsons.zip'
gdown.download(url, output, quiet=False)
with zipfile.ZipFile(output, 'r') as zip_ref:
    zip_ref.extractall('jsons')
os.remove("jsons.zip")
```
# Analysis
!![](fig.html)