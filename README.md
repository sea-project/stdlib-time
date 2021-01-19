# stdlib-time

关于时间处理类

## 目录

序号 | 名称 | 描述
---|---|---
1 | timecycle.go | 关于bytes转换的常用方法
2 | `CurrentSecond`         | 当前时间戳(秒级)
3 | `CurrentMilliSecond`    | 当前时间戳(毫秒级)
3 | `GetEarlyYearUnix`      | 获取年初时间(秒级）
3 | `GetEarlyMonthUnix`     | 获取当前月月初时间(秒级）
3 | `GetZeroHourUnix`       | 获取当日零时时间(秒级）
3 | `GetNowHourUnix`        | 获取当前小时时间(秒级）
3 | `GetUnixToFormatString` | 按照给定格式输出给定的时间戳：例：1550116063  2006-01-02 15:04 输出 2019-02-14 11:47
3 | `GetUnixToString`       | 获取给定时间戳的年月日
3 | `GetUnixToHourString`   | 获取指定格式的给定时间戳的小时和分钟数
3 | `GetUnixToMonth`        | 获取指定时间戳对应的月份
3 | `GetUnixToDay`          | 获取指定时间戳对应的日期
3 | `GetUnixToDayTime`      | 获取指定时间戳对应的月份.日期
3 | `GetStringToFormatUnix` | 将时间字符串转换为时间戳
3 | `GetUnixFormatDate`     | 格式化时间戳，获取年月日时分秒

## 单元测试

序号 | 名称 | 说明
---|---|---
1 | timecycle_test.go   | 对string方法进行功能测试
2 | `Test_CurrentSecond`        | 测试当前时间戳(秒级)
3 | `Test_CurrentMilliSecond`   | 测试当前时间戳(毫秒级)
3 | `Test_GetEarlyMonthUnix`    | 测试获取年初时间(秒级）
3 | `Test_GetEarlyYearUnix`     | 测试获取当前月月初时间(秒级）
3 | `Test_GetZeroHourUnix`      | 测试获取当日零时时间(秒级）
3 | `Test_GetNowHourUnix`       | 测试获取当前小时时间(秒级）
3 | `Test_GetUnixToFormatString`| 测试按照给定格式输出给定的时间戳
3 | `Test_GetUnixToString`      | 测试获取给定时间戳的年月日
3 | `Test_GetUnixToHourString`  | 测试获取指定格式的给定时间戳的小时和分钟数
3 | `Test_GetUnixToMonth`       | 测试获取指定时间戳对应的月份
3 | `Test_GetUnixToDayTime`     | 测试获取指定时间戳对应的月份.日期
3 | `Test_GetStringToFormatUnix`| 测试将时间字符串转换为时间戳
3 | `TestGetUnixFormatDate`     | 测试格式化时间戳

