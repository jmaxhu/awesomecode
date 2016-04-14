# 概述
[ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite)是基于.NET的ORM工具，提供了对多种数据库（目前包含： Sql Server, Sqlite, MySql, PostgreSql, Firebird）的支持。
它提供了一些 System.Data命名空间中的类（主要是IDbConnection)的扩展方法。提供一个POCO类与一个RDBMS表的映射。另外还提供了根据POCO类来Create/Drop表的接口。并且同时支持.NET和Mono平台。

# 安装
可以直接在项目中使用NuGet方式安装。
[![Download on NuGet](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/release-notes/install-ormlite.png)](https://www.nuget.org/packages?q=servicestack+ormlite)

针对不能数据库，共有如下几个库。

- [ServiceStack.OrmLite.SqlServer](http://nuget.org/List/Packages/ServiceStack.OrmLite.SqlServer)
- [ServiceStack.OrmLite.PostgreSQL](http://nuget.org/List/Packages/ServiceStack.OrmLite.PostgreSQL)
- [ServiceStack.OrmLite.MySql](http://nuget.org/List/Packages/ServiceStack.OrmLite.MySql)
- [ServiceStack.OrmLite.Sqlite.Mono](http://nuget.org/packages/ServiceStack.OrmLite.Sqlite.Mono) - Compatible with Mono / Windows (x86)
- [ServiceStack.OrmLite.Sqlite.Windows](http://nuget.org/List/Packages/ServiceStack.OrmLite.Sqlite.Windows) - 32/64bit Mixed mode .NET for Windows only
- [ServiceStack.OrmLite.Oracle](http://nuget.org/packages/ServiceStack.OrmLite.Oracle) (非官方)
- [ServiceStack.OrmLite.Firebird](http://nuget.org/List/Packages/ServiceStack.OrmLite.Firebird)  (非官方)
- [ServiceStack.OrmLite.VistaDb](http://nuget.org/List/Packages/ServiceStack.OrmLite.VistaDb)  (非官方)

# 使用

# 例子
