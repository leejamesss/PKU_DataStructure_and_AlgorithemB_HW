# 题目
圣诞节来临了，圣诞老人准备分发糖果，现
在有多箱不同的糖果，每箱糖果有自己的价值和重
量，每箱糖果都可以拆分成任意散装组合带走。圣
诞老人的驯鹿雪橇最多只能装下重量W的糖果，请
问圣诞老人最多能带走多大价值的糖果。


# 解法：
按礼物的价值/重量比从大到小依次选取礼物，对选
取的礼物尽可能多地装，直到达到总重量w
# 复杂度： 
O(nlogn)
