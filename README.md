# Movie_Market_Analysis

## 1. 数据来源与挖掘概述

### 数据来源：
- 中国官方电影数据信息网：[https://www.zgdypw.cn/sc/sjbg/index_7.shtml](https://www.zgdypw.cn/sc/sjbg/index_7.shtml)
- 猫眼（票房、票价、评分、题材、时长）: [https://piaofang.maoyan.com/rankings/year?year=2024](https://piaofang.maoyan.com/rankings/year?year=2024)
- 豆瓣

### 方法：
使用爬虫技术获取 2024 年电影数据，清洗缺失值、转换数据类型。

### 备注：
仅用于学习目的，尊重数据版权。

---

## 2. 年份（2015-2024 年票房趋势）

### 数据：
- 2015-2024 年总票房趋势。
- 2019 高峰：641 亿元
- 2020 低谷：203 亿元
- 2024 回升：425 亿元

### 洞察：
- 疫情后市场复苏，2024 年表现平稳。
- 2024 年内地电影市场总票房为 425.02 亿元，同比 2023 年下降 22.6%。
- 观影人次为 10.1 亿元，同比下降 22.3%。
- 放映场次为 1.41 亿元，同比下降 8.4%。

### 图表：
- 2015-2024年票房趋势图。

---![image](https://github.com/user-attachments/assets/ae47bd29-2c81-4339-978c-361c2698238e)


## 3. 2024 年月度票房、人次与平均票价趋势

### 票房趋势分析：
- 2月春节档票房达到全年最高峰。
- 3月受进口片带动，票房创新高。
- 5月五一档票房强势反弹，创下档期影史第二佳绩。
- 10月国庆档推动票房回升，但整体回暖有限。
- 4月、6-8月暑期档、9月、11-12月市场表现较为平淡。

### 洞察：
- 票房高度依赖档期效应，春节档、五一档、国庆档是全年关键票房节点。
- 票价稳定性较强（40-48元），票价波动较小，观影需求受影片内容和档期影响更大。
- 商业策略建议：集中资源推广春节和国庆档，淡季通过低价促销或小成本影片刺激市场。

### 图表：
- 2024年票房、人次、平均票价趋势图。

---![image](https://github.com/user-attachments/assets/98cc4c45-32ff-4c95-af6e-096fb9069bfc)
![image](https://github.com/user-attachments/assets/a5f0c2a8-945f-4ec3-93ca-82facb15d1c4)
![image](https://github.com/user-attachments/assets/b45b1673-4637-4054-b6a2-40a0d88b1007)
![image](https://github.com/user-attachments/assets/77883f99-0a21-4cad-8bcc-562a95c50f33)





## 4. 各个档期票房表现

### 数据分析：
- 春节档票房贡献最大，远超其他档期。
- 五一档 & 国庆档表现较好，但不及春节档。
- 中秋档 & 清明档票房较低。

### 洞察：
- 春节档仍然是全年票房主力。
- 五一和国庆档具有较强市场吸引力，但与春节档差距较大。

### 图表：
- 插入各档期票房表现的折线图。
- 插入档期票房与非档期票房占比的饼图。
- ![image](https://github.com/user-attachments/assets/5de2f209-bfa0-4ec3-a8b2-3d2e14a4b937)
- ![image](https://github.com/user-attachments/assets/8053800b-18b9-4d01-ad98-2cdd1f797ec5)
- ![image](https://github.com/user-attachments/assets/1aa75529-5ef2-415d-a5ef-e6faa7e6fc6e)
- ![image](https://github.com/user-attachments/assets/f9e56ab3-7f0b-42d6-bedc-16c19c1e8efa)





---

## 5. 特性分析

### 电影类型（题材占比，前 15）

### 数据分析：
- 2024 年电影题材偏好：剧情片（53%）、喜剧片（21.6%）、动作片（10.1%）。
- 头部电影影响大，市场对某些类型（如喜剧、动画）的依赖性较强。

### 洞察：
- 剧情片占主导，喜剧和动作类型有投资潜力。

### 图表：
- 2024年电影类型分布的饼图。
- 不同类型电影票房的相关性分析。
![image](https://github.com/user-attachments/assets/574d4c1d-cfa2-4576-9fda-8406e7695855)
![image](https://github.com/user-attachments/assets/baaa0b9a-85ec-4a4e-8e5e-e4e7e20d5b05)
![image](https://github.com/user-attachments/assets/a29e1371-a28f-40ac-b298-1692d9b9ca69)
![image](https://github.com/user-attachments/assets/8d629402-9d16-4468-b292-c8678a12a0b9)




---

## 6. 电影时长分布 & 时长 vs. 豆瓣评分

### 数据分析：
- 电影时长主要集中在 90-130 分钟之间。
- 电影时长与豆瓣评分的相关系数较低（0.22），但90-150分钟时长区间的电影质量较高。

### 洞察：
- 90-130 分钟是市场主流时长。
- 电影时长对评分影响较小，关键仍然是电影质量。

### 图表：
- 插入电影时长分布图。

---

## 7. 电影票价分布 & 票价与票房/评分关系

### 数据分析：
- 票价稳定在 35-50 元之间，极高票价（80-100 元）的电影较少。
- 票价与电影票房、评分关系不大，但高票价适用于特定类型的电影（如科幻、战争、大制作等）。

### 洞察：
- 对于一般电影，票价应维持在40-50元区间，而特定类型如IMAX、3D电影可以适当提高票价。
![image](https://github.com/user-attachments/assets/bfe586be-b818-45ca-b17b-b89da0514605)
![image](https://github.com/user-attachments/assets/0b85f6f7-37fa-4d69-8a3a-3519475ebd26)


### 图表：
- 插入票价分布图。

---![image](https://github.com/user-attachments/assets/95f3ba30-d3e3-4ed8-b8ba-63d4b30d5b1d)
![image](https://github.com/user-attachments/assets/e8799e3c-2229-4852-b233-c3bae3568d59)
![image](https://github.com/user-attachments/assets/1bef0186-9b8a-4082-9c9d-9334d617b2d4)




## 8. 各个省份观影情况

### 数据分析：
- 广东省观影人数最高，其次为北京。
- 东部沿海省份观影人数较多，西部偏少。

### 洞察：
- 一线城市票房贡献较大，内陆地区有较大增长潜力。

### 图表：
- ![image](https://github.com/user-attachments/assets/f7319a6d-21e7-4d41-aacf-1237586c91f1)
- ![image](https://github.com/user-attachments/assets/1992826b-9e10-4f90-89e1-6d6bfe9b5ce6)



---

## 9. 观影人次 vs. 票房

### 数据分析：
- 人次与票房正相关，宣传效应显著。
- 票房高的电影通常有更多观众参与。
![image](https://github.com/user-attachments/assets/802e6683-22fd-40fc-a586-c5038b86dae6)
![image](https://github.com/user-attachments/assets/fb37bc95-51fe-4f14-912c-69645df6e0b5)
![image](https://github.com/user-attachments/assets/cac0d496-fe03-4d14-ba1f-f03bc3d64774)



---

## 10. 连续三个月上榜电影的票房金额

### 数据分析：
- 长尾电影票房表现显著，如《抓娃娃》和《志愿军：存亡之战》等。
  
### 洞察：
- 长尾效应在电影市场中明显，档期电影持续表现良好。

---![image](https://github.com/user-attachments/assets/bfcfdd0b-4ed8-4cf5-aebb-3afc8305ec79)
![image](https://github.com/user-attachments/assets/ba704ff1-44e9-4cc6-9004-287ee99aedb5)
![image](https://github.com/user-attachments/assets/65030cef-fef8-4afa-a067-a3019faf4533)
![image](https://github.com/user-attachments/assets/52f0902a-e2ca-413e-8f89-2466b279a994)





## 结论

- 电影市场高度依赖档期效应，尤其是春节档、五一档和国庆档。
- 票价波动较小，主流票价区间为40-50元，市场对票价较高的电影接受度有限。
- 电影类型方面，剧情片占主导地位，喜剧、动画等类型具备较强的市场吸引力。
- 市场趋于稳定，但部分区域（如内陆地区）存在增长潜力。

---

## 备注
此项目仅用于学习目的，所有数据均来源于公开平台，遵循相关版权规定。
