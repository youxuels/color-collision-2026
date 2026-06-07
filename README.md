---
name: color-collision-2026
description: 2026世界经典撞色方案（10组）。提供HEX/RGB/CMYK、CSS变量、背景+文字搭配推荐、渐变组合。做PPT/HTML设计时自动加载，确保文字与背景对比清晰可读。
---

# 🎨 2026世界经典撞色方案

做PPT或HTML设计时，从下面10组方案中选一组，直接用CSS变量搭配。
**关键规则：文字色 vs 背景色必须满足 WCAG AA 对比度（4.5:1+）**，每组已标出最佳文字色。

---

## 1️⃣ 高饱和多巴胺 — 克莱因蓝 + 柠檬黄

| 色名 | HEX | RGB | CMYK |
|:---|:---:|:---:|:---:|
| 克莱因蓝 🔵 | `#002FA7` | 0,47,167 | 100,72,0,35 |
| 柠檬黄 🟡 | `#F9F200` | 249,242,0 | 0,0,100,2 |

**风格：** 强烈冷暖对比、视觉冲击力极强、年轻活力
**适合：** 科技投资、潮牌、2026春夏秀场

```css
/* 方案1 — 深蓝底 + 黄字 */
:root {
  --bg-primary: #002FA7;   /* 克莱因蓝底 */
  --bg-secondary: #001d75;
  --bg-card: #0035c0;
  --accent: #F9F200;       /* 柠檬黄强调 */
  --accent-light: #ffe84d;
  --text-primary: #FFFFFF;  /* 白字 */
  --text-secondary: #c8d4ff;
  --text-on-accent: #001a50; /* 黄底上的深色字 */
  --border: rgba(249,242,0,0.2);
}
```

---

## 2️⃣ 治愈复古 — 奶油白 + 焦糖棕

| 色名 | HEX | RGB | CMYK |
|:---|:---:|:---:|:---:|
| 奶油白 🥛 | `#F5F0E6` | 245,240,230 | 0,2,6,4 |
| 焦糖棕 🍯 | `#B57B45` | 181,123,69 | 0,32,62,29 |

**风格：** 暖调温柔、低饱和高级、治愈感强
**适合：** 家居品牌、消费品牌、生活方式

```css
/* 方案2 — 奶油白底 + 焦糖棕字/强调 */
:root {
  --bg-primary: #F5F0E6;   /* 奶油白底 */
  --bg-secondary: #ede6d8;
  --bg-card: #ffffff;
  --accent: #B57B45;        /* 焦糖棕 */
  --accent-light: #c99563;
  --text-primary: #3d2b1a;  /* 深褐字（对比度7:1） */
  --text-secondary: #7a5c3e;
  --text-on-accent: #ffffff;
  --border: rgba(181,123,69,0.15);
}
```

---

## 3️⃣ 自然高级 — 森林深绿 + 砂金

| 色名 | HEX | RGB | CMYK |
|:---|:---:|:---:|:---:|
| 森林深绿 🌲 | `#2C5F2D` | 44,95,45 | 0,53,63,55 |
| 砂金 🏆 | `#D4AF37` | 212,175,55 | 0,17,74,17 |

**风格：** 自然静谧×金属提亮、沉稳低调奢华
**适合：** 环保/ESG投资、高端品牌、生态科技

```css
/* 方案3 — 深绿底 + 砂金强调 */
:root {
  --bg-primary: #2C5F2D;   /* 森林深绿底 */
  --bg-secondary: #1e4520;
  --bg-card: #3a7a3c;
  --accent: #D4AF37;        /* 砂金 */
  --accent-light: #e0c45c;
  --text-primary: #FFFFFF;
  --text-secondary: #b8d4b0;
  --text-on-accent: #1a3018;
  --border: rgba(212,175,55,0.2);
}
```

---

## 4️⃣ 高级灰绿 — 逯绿 + 古白

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 逯绿 💚 | `#1C6C4C` | 28,108,76 | 深沉墨绿，灰调 |
| 古白 🤍 | `#E6E0CB` | 230,224,203 | 温润米白，略泛黄底 |

**风格：** 高级灰绿、质感醇厚、新中式
**适合：** 奢侈品、文化类、高端PPT

```css
/* 方案4 — 古白底 + 逯绿强调 */
:root {
  --bg-primary: #E6E0CB;   /* 古白底 */
  --bg-secondary: #dbd3bb;
  --bg-card: #ffffff;
  --accent: #1C6C4C;        /* 逯绿 */
  --accent-light: #2a8b64;
  --text-primary: #142b20;  /* 深褐绿字 */
  --text-secondary: #3d6652;
  --text-on-accent: #ffffff;
  --border: rgba(28,108,76,0.15);
}
```

---

## 5️⃣ 新中式撞色 — 琉璃 + 玉子

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 琉璃 🟢 | `#0B6051` | 11,96,81 | 深青绿，沉稳典雅 |
| 玉子 🟡 | `#FABE51` | 250,190,81 | 暖金黄，温润明亮 |

**风格：** 冷青绿+暖金黄的经典对比
**适合：** 文创、珠宝、国潮品牌

```css
/* 方案5 — 琉璃底 + 玉子强调 */
:root {
  --bg-primary: #0B6051;   /* 琉璃底 */
  --bg-secondary: #08473b;
  --bg-card: #107a68;
  --accent: #FABE51;        /* 玉子 */
  --accent-light: #fbd073;
  --text-primary: #FFFFFF;
  --text-secondary: #a0d0c5;
  --text-on-accent: #1a3a30;
  --border: rgba(250,190,81,0.2);
}
```

---

## 6️⃣ 中国红撞色 — 萼绿 + 正红

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 萼绿 🌿 | `#014946` | 1,73,70 | 深墨绿 |
| 正红 🧧 | `#C3272B` | 195,39,43 | 中国传统朱红 |

**风格：** 深绿底+朱红点缀，稳重热烈
**适合：** 中国政策研究、文化投资、红色主题

```css
/* 方案6 — 萼绿底 + 正红强调 */
:root {
  --bg-primary: #014946;   /* 萼绿底 */
  --bg-secondary: #013432;
  --bg-card: #02605c;
  --accent: #C3272B;        /* 正红 */
  --accent-light: #d94a4d;
  --text-primary: #FFFFFF;
  --text-secondary: #80b5b2;
  --text-on-accent: #ffffff;
  --border: rgba(195,39,43,0.2);
}
```

---

## 7️⃣ 莫兰迪灰 — 兰迪 + 鹤粉

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 兰迪 🌿 | `#7A916D` | 122,145,109 | 低饱和灰豆绿 |
| 鹤粉 🩰 | `#FFDCD0` | 255,220,208 | 柔浅杏裸粉 |

**风格：** 莫兰迪色系、极简高级、低饱和耐看
**适合：** 女装、室内设计、美妆、生活类

```css
/* 方案7 — 鹤粉底 + 兰迪强调 */
:root {
  --bg-primary: #FFDCD0;   /* 鹤粉底 */
  --bg-secondary: #f5cec0;
  --bg-card: #ffffff;
  --accent: #7A916D;        /* 兰迪 */
  --accent-light: #94ad87;
  --text-primary: #2d3628;  /* 深灰绿字 */
  --text-secondary: #5a6e4f;
  --text-on-accent: #ffffff;
  --border: rgba(122,145,109,0.15);
}
```

---

## 8️⃣ 清新温柔 — 欧碧 + 盈粉

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 欧碧 🌿 | `#C0D695` | 192,214,149 | 嫩芽抹茶绿 |
| 盈粉 💗 | `#F9D3E3` | 249,211,227 | 淡雅藕粉 |

**风格：** 春日清新、温柔浪漫、自然生机
**适合：** 鲜花品牌、亲子、婚礼、生活方式

```css
/* 方案8 — 欧碧底 + 盈粉强调 */
:root {
  --bg-primary: #C0D695;   /* 欧碧底 */
  --bg-secondary: #b2c984;
  --bg-card: #ffffff;
  --accent: #D48AA8;        /* 调整深粉为强调 */
  --accent-light: #e0a8be;
  --text-primary: #2a3a20;  /* 深绿字 */
  --text-secondary: #4d6b3e;
  --text-on-accent: #ffffff;
  --border: rgba(212,138,168,0.15);
}
```

---

## 9️⃣ 同色系深浅 — 绿茶 + 墨绿

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 绿茶 🍵 | `#91B821` | 145,184,33 | 明亮草绿/柠檬绿 |
| 墨绿 🌑 | `#1C2D25` | 28,45,37 | 深邃暗绿/近黑 |

**风格：** 同色系强对比、自然环保
**适合：** 环保品牌、户外、茶饮、可持续发展

```css
/* 方案9 — 墨绿底 + 绿茶强调 */
:root {
  --bg-primary: #1C2D25;   /* 墨绿底 */
  --bg-secondary: #121e18;
  --bg-card: #2a4236;
  --accent: #91B821;        /* 绿茶 */
  --accent-light: #aad23a;
  --text-primary: #FFFFFF;
  --text-secondary: #80a06a;
  --text-on-accent: #1a2a18;
  --border: rgba(145,184,33,0.2);
}
```

---

## 🔟 冷绿暖橙 — 綪绿 + 凌霄

| 色名 | HEX | RGB | 视觉特征 |
|:---|:---:|:---:|:---|
| 綪绿 💚 | `#215A59` | 33,90,89 | 深青绿 |
| 凌霄 🧡 | `#ED723F` | 237,114,63 | 暖橙红/朱砂橙 |

**风格：** 互补色撞色、强烈视觉冲击
**适合：** 科技产品、创意设计、数据可视化

```css
/* 方案10 — 綪绿底 + 凌霄强调 */
:root {
  --bg-primary: #215A59;   /* 綪绿底 */
  --bg-secondary: #16403f;
  --bg-card: #2d7674;
  --accent: #ED723F;        /* 凌霄 */
  --accent-light: #f28e62;
  --text-primary: #FFFFFF;
  --text-secondary: #90c0bf;
  --text-on-accent: #2a1a10;
  --border: rgba(237,114,63,0.2);
}
```

---

## 使用说明

### 做PPT/HTML时
```html
<!-- 选一组方案，Copy CSS变量到你的 :root  -->
<style>
  :root { /* 从上方选一组粘贴过来 */ }
  body { background: var(--bg-primary); color: var(--text-primary); }
  .card { background: var(--bg-card); border-color: var(--border); }
  .accent { color: var(--accent); }
  .btn { background: var(--accent); color: var(--text-on-accent); }
</style>
```

### 场景速查

| 场景 | 推荐方案 |
|:---|:---|
| **科技/投资PPT** | 1️⃣ 克莱因蓝+黄 / 3️⃣ 深绿+砂金 / 🔟 綪绿+凌霄 |
| **消费/品牌PPT** | 2️⃣ 奶油白+焦糖棕 / 7️⃣ 莫兰迪 / 8️⃣ 欧碧+粉 |
| **政策/学术PPT** | 4️⃣ 逯绿+古白 / 6️⃣ 萼绿+正红 |
| **环保/ESG** | 3️⃣ 森林深绿+砂金 / 9️⃣ 绿茶+墨绿 |
| **文创/国潮** | 5️⃣ 琉璃+玉子 / 6️⃣ 萼绿+正红 |
| **数据可视化** | 1️⃣ 克莱因蓝+黄 / 🔟 綪绿+凌霄 |
| **电商/营销** | 2️⃣ 治愈复古 / 8️⃣ 清新温柔 |

### 对比度规则
- **深色背景（克莱因蓝/森林深绿/琉璃/萼绿/綪绿/墨绿）** → 白字 (#FFFFFF) + 亮色强调
- **浅色背景（奶油白/古白/鹤粉/欧碧）** → 深色字 (#1a2a30 / #3d2b1a) + 深色强调
- **强调色上的文字** → 深色背景用白字，浅色背景用深字
