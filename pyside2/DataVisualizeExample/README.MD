
## Source : https://wiki.qt.io/Qt_for_Python_Tutorial:_Data_Visualization_Tool


## I modify 1 place in the code

# I have add the following 

```python
import os
import PySide2

dirname = os.path.dirname(PySide2.__file__)

plugin_path = os.path.join(dirname, 'plugins', 'platforms')
os.environ['QT_QPA_PLATFORM_PLUGIN_PATH'] = plugin_path
```