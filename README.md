## Pytest实战作业
要求：
- 1、补全计算器（加减乘除）的测试用例
- 2、使用参数完成测试用例的自动生成
- 3、在调用测试方法之前打印【开始计算】，在调用测试方法之后打印【计算结束】
### 练习1
- 使用【测试数据的数据驱动】的方法完成加减乘除测试
- 使用fixture替换setup和teardown
- 将fixture方法放在conftest.py里面，设置scope=module
- 修改运行规则，pytest.ini文件
### 练习2(选做)
- 控制用例的执行顺序，如：加减乘除
- 结合allure生成测试结果报告
### Selenium 作业1
使用序列化cookie的方式 登录企业微信，完成添加联系人，加上断言验证a