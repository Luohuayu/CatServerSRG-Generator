# CatServerSRG-Generator
用于生成CatServerSRG依赖的工具

使用方法:<br>
1. 构建CatServer项目<br>
2. 复制CatServer项目的/build/localCache/Catserver/recompiled.jar到工具目录<br>
3. 运行genSrg.bat生成remapped.jar<br>
4. 导入remapped.jar作为依赖

---
A Tool for generating CatServerSRG dependencies

How to use: <br>
1. Build CatServer project <br>
2. Copy /build/localCache/Catserver/recompiled.jar of the CatServer project to the tool directory <br>
3. Run genSrg.bat to generate remapped.jar <br>
4. Import remapped.jar as a dependency