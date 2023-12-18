# 为Jupyter安装C#核心

**在Jupyter Lab中使用C#语言(安装.NET/C#内核)**

- 安装Anaconda(1.12.0)
- [安装.NET](http://安装.NET) 7.0 SDK或者Visual Studio 2022
- 运行 `python --version` 查看Python版本号(3.11.4)
- 运行 `dotnet --version` 查看.NET版本号(7.0.400)
- 运行 `dotnet tool install -g Microsoft.dotnet-interactive` [安装.NET](http://安装.NET) Interactive组件(1.0.446104)
- 运行 `dotnet interactive jupyter install` 安装Jupyter .NET(C#)内核
- 出现无法安装错误，手动创建kernals文件夹

![](csharp-kernal-installation.png)

参考：

- [C# Jupyter Notebooks (servicestack.net)](https://docs.servicestack.net/jupyter-notebooks-csharp#generate-c-jupyter-notebooks)