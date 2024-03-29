---
id: 5e46f7e5ac417301a38fb929
title: 人口統計數據分析器
challengeType: 10
forumTopicId: 462367
dashedName: demographic-data-analyzer
---

# --description--

You will be <a href="https://gitpod.io/?autostart=true#https://github.com/freeCodeCamp/boilerplate-demographic-data-analyzer/" target="_blank" rel="noopener noreferrer nofollow">working on this project with our Gitpod starter code</a>.

我們仍在開發 Python 課程的交互式教學部分。 目前，你可以在 YouTube 上通過 freeCodeCamp.org 上傳的一些視頻學習這個項目相關的知識。

- <a href="https://www.freecodecamp.org/news/python-for-everybody/" target="_blank" rel="noopener noreferrer nofollow">給所有人的 Python 課程</a>（14 小時）

- <a href="https://www.freecodecamp.org/news/how-to-analyze-data-with-python-pandas/" target="_blank" rel="noopener noreferrer nofollow">如何使用 Python Pandas 分析數據</a>（10 小時）

# --instructions--

在這個挑戰中，你必須使用 Pandas 對人口統計進行分析。 你將獲得從 1994 年人口普查數據庫中提取的人口統計數據數據集。 以下是數據的示例：

```markdown
|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week | native-country   | salary   |
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|:-----------------|:---------|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | United-States    | <=50K    |
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | United-States    | <=50K    |
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 | Cuba             | <=50K    |
```

你必須使用 Pandas 來回答以下問題：

- 這個數據集中每個種族有多少人？ 這應該是一個以種族名稱作爲索引標籤的 Pandas 系列。 （`race` 欄）
- 男性的平均年齡是多少？
- 擁有學士學位的人的百分比是多少？
- 受過高等教育（`Bachelors`、`Masters` 或 `Doctorate`）且收入超過 50K 的人佔多大比例？
- 沒有受過高等教育且收入超過 50K 的人的比例是多少？
- 一個人每週最少工作多少小時？
- 每週工作最少小時數的人中有多少人的工資超過 50K？
- 哪個國家/地區的收入 >50K 的人口比例最高，該比例是多少？
- 找出印度收入 >50K 的人最受歡迎的職業。

Use the starter code in the file `demographic_data_analyzer.py`. Update the code so all variables set to `None` are set to the appropriate calculation or code. 將所有小數四捨五入到最接近的十分之一。

## 開發

Write your code in `demographic_data_analyzer.py`. For development, you can use `main.py` to test your code.

## 測試

The unit tests for this project are in `test_module.py`. 爲了你的方便，我們將測試從 `test_module.py` 導入到 `main.py`。

## 提交

複製項目的 URL 並將其提交給 freeCodeCamp。

## 數據集源

Dua, D. and Graff, C. (2019). <a href="http://archive.ics.uci.edu/ml" target="_blank" rel="noopener noreferrer nofollow">UCI Machine Learning Repository</a>. Irvine, CA: University of California, School of Information and Computer Science.

# --hints--

它應該通過所有的 Python 測試。

```js

```

# --solutions--

```py
  # Python challenges don't need solutions,
  # because they would need to be tested against a full working project.
  # Please check our contributing guidelines to learn more.
```
