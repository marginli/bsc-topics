# BSC 專題課程總覽

把各個專題課程網頁收在同一個入口。線上版：`https://marginli.github.io/<本 repo 名>`
（`robots.txt` 擋掉搜尋引擎索引，跟各專題站一致）。

## 這個 repo 有什麼

| 路徑 | 是什麼 |
|---|---|
| `index.html` | 總覽頁：每個專題一張卡片 |
| `assets/bsc.css` | 樣式。**從 `VFB/assets/vfb.css` 裁出來的骨架** |

## 加一個新專題要改的地方

只有一處：`index.html` 的 `<div class="btns">` 裡多一張 `<a class="btn …">` 卡片。
卡片的四個部分依序是——`.no`（專題編號）、`.t`（標題）、`.s`（一段話）、
`ul.meta`（四個標記：幾個部分、錨是什麼、怎麼查證、需要什麼基礎）。
配色靠 `c2`／`c3`／`c4`／`c5` 這幾個 class 輪替。

**不要在這裡重寫專題的介紹**——卡片上那段話要跟該專題自己首頁的講法一致，
改了那邊就要回來改這邊（核心規範第 12 節〈跨頁一致性〉）。

## 視覺改動要三個檔案一起改

`assets/bsc.css`、`VFB/assets/vfb.css`、`LPU/assets/lpu.css` 用的是同一組設計變數
（`--ink`／`--accent`／`--maxw` 那一組）。三個站看起來是一套，是因為變數一樣；
只改其中一個，三個站就會開始長得不一樣。

## 本機原始碼

`BSC_plan/specific_topics/hub/`。各專題的原始碼在它旁邊的 `LPU/`、`VFB/`。

教學用途，非營利。
