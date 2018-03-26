# 电视动画播出信息

自 1959 年至 2018 年 1 月日本电视动画的播出信息。

## 数据来源
原始数据来自于[テレビドラマデータベース](http://www.tvdrama-db.com/)，选取了连续电视动画。并通过以下网站补充及修正数据，重要性按先后顺序递减：
* [日本维基百科](https://ja.wikipedia.org/wiki/%E3%83%A1%E3%82%A4%E3%83%B3%E3%83%9A%E3%83%BC%E3%82%B8)
* [映画データベース - allcinema](http://www.allcinema.net/prog/index2.php)
* [アニメ情報調査室](http://www.anime.marumegane.com/)
* [MyAnimeList.net](https://myanimelist.net/)
* [メディア芸術データベース](https://mediaarts-db.bunka.go.jp/?locale=ja&display_view=sp)
* 动画官方网站

## 数据说明
数据为纯文本文件，采用制表符（ tab ）分隔字段。
### ID
每部作品的唯一标识，最长 5 位数，源自[テレビドラマデータベース](http://www.tvdrama-db.com/)。部分作品 ID 为 6 位数并以`00`结尾，为[テレビドラマデータベース](http://www.tvdrama-db.com/)缺少的作品。 

### 标题
作品的标题，来自[テレビドラマデータベース](http://www.tvdrama-db.com/)。标题中的`(1)`、`(2)`对应`第一季`等内容。

### 首播日期、完结日期
日期格式为`YYYY/MM/DD`。

### 播出日
使用日本的曜日记法。对应如下：
* 日（曜日）：星期日
* 月（曜日）：星期一
* 火（曜日）：星期二
* 水（曜日）：星期三
* 木（曜日）：星期四
* 金（曜日）：星期五
* 土（曜日）：星期六

### 播出时间、结束时间
采用 30 小时制，一天为 30 小时。比如`1996/01/03`凌晨`01:00`播出的作品，会记录为`1996/01/02`年的`25:00`播出。需要 24 小时制时间的，注意转换。

### 电视台简称、电视名称
首播电视台的简称和名称。

### 电视台类型
* earth：地上波
* cs：采用通讯卫星广播的卫星电视台
* bs：采用广播卫星广播的卫星电视台
* nhk：NHK 系的电视台
* uhf：所有独立电视台，不光是超短波广播电视台。

## 注意事项
1. 1996 年之前的数据缺失比较严重。
2. 仅有小部分数据（ 120 条左右）经过人工补充和核对，其余数据皆为原始数据。
3. 人工补充和核对数据全部来源于网络。
