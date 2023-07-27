# 2023年最新全国省市区县镇居委会sql+json

#### sql脚本导入时，先创建以下表，再执行脚本导入
- 表结构
    ``` 
    CREATE TABLE `dict_region` (
      `code` CHAR(36) DEFAULT NULL,
      `name` VARCHAR(765) DEFAULT NULL,
      `parent_code` CHAR(36) DEFAULT NULL,
      `level` INT DEFAULT NULL
    ) ENGINE=INNODB DEFAULT CHARSET=utf8mb4

    ```
