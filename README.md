# wangcaitao-dependencies-parent

统一管理 jar 包版本

## 使用

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>cn.wangcaitao</groupId>
            <artifactId>wangcaitao-dependencies</artifactId>
            <version>${last.version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```