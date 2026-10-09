# 伊莫 Aniimo｜屬性剋制計算器 Type Calculator

**繁體中文 | [English](#english)**

一個為《伊莫 Aniimo》玩家製作的網頁屬性剋制計算工具，協助玩家快速研究屬性搭配、分析隊伍弱點與抗性。

An interactive, web-based type effectiveness calculator for **Aniimo**, designed to help players explore type combinations, analyze team weaknesses, and plan their teams.

---

<a id="繁體中文"></a>

## 🇹🇼 繁體中文

### ✨ 功能介紹

**1. 隊伍屬性配置｜Team Builder**

- 支援我方與敵方各 4 個隊伍位置。
- 每個位置最多設定 2 種屬性。
- 自動計算每個位置的弱點（Weak）與抗性（Resist）。
- 支援快速清空隊伍與自動儲存配置。

**2. 隊伍分析｜Team Analysis**

- 同時分析我方與敵方隊伍。
- 統計各種攻擊屬性對隊伍造成弱點或產生抗性的次數。
- Weak 與 Resist 分別顯示。
- 依照數量由高至低排序，快速辨識隊伍的主要弱點。

**3. 拖曳操作｜Drag & Drop**

- 將任意屬性圖標拖曳至隊伍位置即可套用。
- 支援跨隊伍屬性配置。
- 將隊伍中的屬性拖至空白區域可直接清除。
- 保留點擊選擇屬性的傳統操作方式。

**4. 屬性研究｜Type Explorer**

- 支援草、火、電、土、風、水、光、暗、冰，共 9 種屬性。
- 比較單屬性及雙屬性的弱點與抗性。
- 特別標示雙重弱點與雙重抗性。

**5. 屬性關係網｜Relationship Network**

- 以 SVG 視覺化呈現屬性剋制關係。
- 透過連線顏色、粗細與倍率區分效果。
- 雙屬性圖標可在中心公轉，圖標本身保持正向。
- 支援從關係網直接拖曳屬性至隊伍位置。

### 🎮 使用方法

1. 點擊我方或敵方隊伍的屬性欄位，選擇屬性。
2. 查看自動計算的 Weak 與 Resist。
3. 點擊「分析 Analysis」，比較雙方隊伍整體弱點與抗性。
4. 在「屬性研究 Type Explorer」中選擇主屬性，查看不同屬性組合。
5. 點擊比較表中的組合，即可更新右側關係網。
6. 也可拖曳屬性圖標，快速配置隊伍。

### 📊 屬性倍率

| 屬性效果 | 倍率 |
|---|---:|
| 雙重弱點 | 2.56× |
| 弱點 | 1.6× |
| 一般 | 1× |
| 抗性 | 0.625× |
| 雙重抗性 | 0.390625× |

雙屬性使用倍率相乘方式計算。此為工具目前採用的計算模型，並非已確認的官方機制。

---

<a id="english"></a>

## 🇬🇧 English

### ✨ Features

**1. Team Builder**

- Configure up to 4 slots for both your team and the enemy team.
- Assign up to 2 types to each slot.
- Automatically calculate weaknesses and resistances.
- Clear team configurations instantly.
- Automatically save your configurations locally.

**2. Team Analysis**

- Analyze both teams simultaneously.
- Count how many team slots are weak or resistant to each attacking type.
- Display Weak and Resist results separately.
- Sort results from highest to lowest count.
- Quickly identify major defensive vulnerabilities.

**3. Drag & Drop**

- Drag any type icon onto a team slot to assign it.
- Assign types across your team and the enemy team.
- Drag an assigned type outside a valid team slot to remove it.
- Traditional click-to-select controls are also available.

**4. Type Explorer**

- Explore all 9 types: Grass, Fire, Electric, Earth, Wind, Water, Light, Dark, and Ice.
- Compare single-type and dual-type combinations.
- Review the weaknesses and resistances of each combination.
- Highlight double weaknesses and double resistances.

**5. Relationship Network**

- Visualize type effectiveness with an interactive SVG network.
- Distinguish effectiveness using line colors, thickness, and multipliers.
- Dual-type icons orbit around the center while remaining upright.
- Drag type icons directly from the network into team slots.

### 🎮 How to Use

1. Click a type slot under **My Team** or **Enemy Team**.
2. Select one or two types.
3. Review the automatically calculated Weak and Resist results.
4. Click **Analysis** to compare both teams' overall weaknesses and resistances.
5. Select a primary type in **Type Explorer** to compare different combinations.
6. Click a combination in the table to update the relationship network.
7. Drag and drop type icons to quickly configure your teams.

### 📊 Effectiveness Multipliers

| Effect | Multiplier |
|---|---:|
| Double Weakness | 2.56× |
| Weakness | 1.6× |
| Neutral | 1× |
| Resistance | 0.625× |
| Double Resistance | 0.390625× |

Dual-type effectiveness is calculated by multiplying the effectiveness values of both defensive types.

**Note:** This is the calculation model currently used by the tool. It has not been confirmed as an official game mechanic.

---

## 🛠️ 技術架構｜Tech Stack

| 技術 Technology | 用途 Purpose |
|---|---|
| HTML5 | 網頁結構 / Page structure |
| CSS3 | 響應式介面與動畫 / Responsive UI and animations |
| JavaScript | 屬性計算與互動 / Type calculations and interactions |
| SVG | 屬性關係網 / Relationship visualization |
| Pointer Events | 滑鼠與觸控拖曳 / Mouse and touch drag-and-drop |
| LocalStorage | 本機儲存配置 / Local configuration storage |
| GitHub Pages | 靜態網站部署 / Static website hosting |

## 📁 專案結構｜Project Structure

```text
/
├── index.html        # Main application
├── attributes.png    # Type icon sprite
└── README.md         # Documentation
```

## 🚀 安裝與部署｜Installation & Deployment

**繁體中文**

1. 下載或 Clone 本專案。
2. 確保 `index.html` 與 `attributes.png` 位於同一資料夾。
3. 使用瀏覽器開啟 `index.html`。

**English**

1. Download or clone this repository.
2. Keep `index.html` and `attributes.png` in the same directory.
3. Open `index.html` in your web browser.

No backend server, database, or additional JavaScript framework is required.

## ⚠️ 免責聲明｜Disclaimer

**繁體中文**

本專案為玩家製作的非官方工具，與《伊莫 Aniimo》官方或其開發、發行單位沒有任何隸屬或合作關係。

遊戲內容與屬性剋制機制可能隨版本更新而有所變動，請以遊戲官方資訊為準。

**English**

This is an unofficial fan-made tool and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Aniimo.

Game mechanics and type effectiveness may change with future updates. Please refer to official game information for accurate and up-to-date details.

---

## ❤️ 專案目標｜Project Goal

**繁體中文**

讓玩家能夠透過簡單直覺的操作，快速理解屬性剋制關係、研究不同屬性組合，並更方便地規劃自己的伊莫隊伍。

**English**

To provide Aniimo players with a simple and intuitive way to understand type effectiveness, explore different type combinations, and make team planning easier and more enjoyable.

---

Made with ❤️ for the Aniimo community.
