一、 php linter:
1. php linter = php -l
2. 用于php语言诊断
3. 控制php-linter:
    php.validate.enable:
        是否启用php-linter
        默认启用
    php.validate.executablePath:
        php可执行文件的路径
            如果系统变量中没有php可执行文件的时候要指定
    php.validate.run:
        保存的时候是否触发诊断（默认为是的）
            别一个选项是 "onType"
            默认值： "onSave"
4. 修改配置
    打开settings
    search: php-->php
    php.validate.executablePath: "/usr/bin/php"