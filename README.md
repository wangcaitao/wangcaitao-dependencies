# wangcaitao-dependencies-parent

统一管理第三方 jar 包版本

## 使用

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.wangcaitao</groupId>
            <artifactId>wangcaitao-dependencies</artifactId>
            <version>2.1.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```