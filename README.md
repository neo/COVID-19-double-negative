# COVID-19-double-negative

It is extremely hard for Chinese citizens to go back to China now during this unprecedented pendamic time:

> In order to reduce cross-border transmission of Covid-19, starting from 7 November, 2020, all Chinese and foreign passengers who are to fly from Canada to China will be required to take nucleic acid and IgM anti-body tests within **two days** before boarding, and provide certificates of negative results of **both tests**.
> –– [Embassy of China, 2020/10/31](http://ca.china-embassy.org/eng/sggg/t1828289.htm)

And this repo is an attampt to hopefully make it slightly easier by sharing and consolidating individual experience.

## 海外各地双阴性检测情况汇总

鉴于现在海外华人归国之路在凭双阴性证明乘机政策实施后变得难上加难，本着开放互联网和开源精神，想尝试在开放可合作的平台让大家可以把自己的亲身体验或者从别的相对封闭平台（诸如微信公众号和小红书等）找到的相关信息分享汇总起来供后来人参考。

### 目录

|                      |                      |     |     |
| :------------------: | :------------------: | :-: | :-: |
| [YYZ 多伦多](YYZ.md) | [YVR 温哥华](YVR.md) |     |     |
|                      |                      |     |     |

### 数据结构

初步设想以出发地/检测地机场代码分类，每一个城市/区域有一个以其机场代号命名的 Markdown 文件，按检测时间顺序从下到上、最近的在最上面排列、同一天的按提交顺序排列。每一项应注明两项检测分别的检测时间、出结果时间、检测地点以及成功与否等信息，亦可包含详情但非必须。

### 模版

```md
## [检测日期 + "成功"/"失败"]

[":satisfied: 成功" 或 ":sob: 失败"]

[作者]：["亲身经历" 或 出处链接]

#### ["核酸"/"抗体"]

- [[检测机构名称地点]]([最好加上预约和其他信息的链接])
- [取样检测的日期时间] 检测
- [收到结果的日期时间] 报告
- [可附加其他重点如排队时间和检测费用等]
- ...

#### ["核酸"/"抗体"]

...

#### 全程（可选）

<details>
<summary>[标题]</summary>
详细过程
...
</details>
```

### 例子

```md
# YYZ 多伦多

## 2020-11-12 成功

:satisfied: 成功

一只干脆面: https://www.xiaohongshu.com/discovery/item/5f9d969b0000000001002c4f

#### 核酸

- [UHN Toronto Western](https://www.uhn.ca/Covid19/Pages/COVID19_assessment_centre.aspx)
- 2020-11-12 11:20 检测
- 2020-11-12 23:31 报告

#### 核酸

- [Mount Sinai Hospital](https://www.sinaihealth.ca/covid19/covid-19-assessment-centre/)
- 2020-11-12 11:45 检测
- 报告时间未注明
- 排队时间久

#### 抗体

- [Dynacare Edward St.](<https://www.dynacare.ca/specialpages/secondarynav/find-a-location/toronto-(5).aspx>>)
- 2020-11-12 13:10 检测
- 2020-11-13 10:00 报告

#### 全程

<details>
<summary>11.14 ✈️ 多伦多-上海·滑铁卢双检测</summary>
行叭，政策改了孩子哭了。

——♦️11.13 更新 ♦️——

纯粹是因为半夜热醒了……一看 Western 已经出报告了。23 点 31 出的，很好很快人不多，推荐一波。

Dynacare 今早上 10 点左右出的结果。

目前暂时是这样，后续会更新的 👀

各位小伙伴不要太过惊慌，有进展我一定会发出来的，希望大家都可以顺利回国

</details>
```

## 分享贡献

欢迎以每一次经历一个 PR 的形式分享，可以是自己亲身经历也可以从其他平台整理的（请注明出处并依照模版的格式）。每一个 PR 下面也可以进行针对某一项经历的具体讨论。

## 最后

**祝愿大家都能早日顺利回国！**

_所有信息未经验证仅供参考。_
