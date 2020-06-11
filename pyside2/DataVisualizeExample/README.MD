
## Source : https://wiki.qt.io/Qt_for_Python_Tutorial:_Data_Visualization_Tool



# Comment and Summary
Main: PySide2.QtWidgets.QHBoxLayout  ,  and then call the addwidget function to add the 

1. PySide2.QtWidgets.QTableView  and   

2. QtCharts.QChartView 
      
   takes the QtCharts.QChart as the input 
   and then add the axis by calling addAxis on the QChart object.
   







## I modify 1 place in the code, I have add the following 

```python
import os
import PySide2

dirname = os.path.dirname(PySide2.__file__)

plugin_path = os.path.join(dirname, 'plugins', 'platforms')
os.environ['QT_QPA_PLATFORM_PLUGIN_PATH'] = plugin_path
```
