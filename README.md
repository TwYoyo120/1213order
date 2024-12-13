# 1213order

調整model

pom檔新增
<!-- Jakarta Bean Validation API -->
    <dependency>
        <groupId>jakarta.validation</groupId>
        <artifactId>jakarta.validation-api</artifactId>
        <version>3.0.2</version>
    </dependency>

    <!-- Hibernate Validator 作為 Bean Validation 的實現 -->
    <dependency>
        <groupId>org.hibernate.validator</groupId>
        <artifactId>hibernate-validator</artifactId>
        <version>7.0.4.Final</version>
    </dependency>

    <!-- 如果需要，還可以添加 Bean Validation 的依賴 -->
    <dependency>
        <groupId>org.glassfish</groupId>
        <artifactId>jakarta.el</artifactId>
        <version>4.0.2</version>
    </dependency>

