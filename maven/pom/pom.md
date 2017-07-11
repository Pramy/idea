# 1.dependency

- ## scope

| name     | scope                                  |
| -------- | -------------------------------------- |
| comlipe  | 默认范围，编译范围，依赖于所有的的classpath，会被打包        |
| provided | 当容器提供了之后才会使用，不会被打包，例如servlet-api       |
| runtime  | 在运行时依赖，编译不依赖，例如jdbc                    |
| test     | test范围依赖 在一般的 编译和运行时都不需要，它们只有在测试编译和测试运 |
| system   | 指定不开源的jar或者非公开的jar。需要设置路径，不打包          |