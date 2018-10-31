## OsmnxProjectDemo

### 复杂网络与社会网络分析大作业
-----------------------------------------

  利用`python`的开源第三方库`Osmnx`，结合旧金山的出租车轨迹数据集和旧金山的**drive**道路网络，进行了一些分析，并将结果可视化出来
  
  * 注意：第一次运行此代码时，请将程序中的代码注释去掉  
  
  * 出租车的轨迹数据集保存在**cabspottingdata**文件夹中 
  
  * **cabspottingdata**文件夹中的每一个**txt**文件（除去一个记录了所有车的编号的**txt**文件）表示一辆车一段时间的轨迹，**txt**文件名即为车辆的唯一标记编号，**txt**文件里面的每一行数据的各个列分别表示为：**纬度 | 经度 | 是否载客（"0"表示空车状态，"1"表示载客状态） | 时间戳**
  
  * **data**文件夹中是我运行程序之后从OpenStreetMap上面下载的旧金山的道路网络以及进行投影之后的道路网络，需要请自行下载使用 
  
  * **image**文件夹是我运行程序之后保存的部分的矢量图(.svg)，需要请自行下载
  
  * 程序运行环境：本程序采用`python 3`编写，所用的IDE为`Jupyter Notebook`。故运行此程序建议安装`Anaconda 3` (当然，`pycharm`也是ok的，不过不如Anaconda方便)，`Anaconda`集成了`Jupyter Notebook`和相关的科学计算的包，另外，此程序正确运行需要安装`Osmnx`和它的依赖库。推荐使用`conda`安装（不建议用`pip`进行安装） 
