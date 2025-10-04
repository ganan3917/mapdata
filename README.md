 ### 本仓库是azerothcore核心，带playerbot模块的地图数据，不带模块也可以使用。
 
 包含以下内容：
 - map
- mmap
- dbc
- vmap
- Cameras
- 增加中文dbc解决机器人的技能问题
- 解压说明：
   1. 若为分片文件（如dataxxx.zip.part00），请先合并：
      - Linux/Mac: `cat dataxxx.zip.part* > dataxxx.zip`
      - Windows: `copy /b dataxxx.zip.part* dataxxx.zip`
   2. 再用rar或zip解压合并后的文件
