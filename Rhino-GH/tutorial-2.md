[Home](../README.md) > [Rhino+GH](./README.md) > Tutorial 2

# Tutorial 2: Math and Design

```
Review: Associated Objects & Parameters 物件與參數關聯性（使用愈少元件愈好）
1. 生成以下數列：
   0, 0, 0, 0, 0, 0, 0, 0, 0, 0 (共10項)
   1, 3, 5, 7, 9, 11, 13, 15, 17, 19 (共10項)
   1, 4, 7, 10, 13, 16, 19, 22, 25, 28 (共10項)
   1, 0, -1, 0, 1, 0, -1, 0, 1, 0,... (多種做法)
   1, 2, 3, 4, 1, 2, 3, 4, 1, 2, 3, 4,...
2. 用 Evaluate Curve 元件對任意曲線取中點
3. 任意N個點，任意一圓Ｃ，請判斷在圓內的點有哪些。
4. 用一般算數元件製作階乘(Factorial)運算
```

## Basics

* Bake 烘焙（實體化）
* Inputs & Pre-process, Outputs & post-process of data in a component 輸入值與前處理、輸出值與後處理
* Implicit vs. Explicit data 隱性與顯性資料
* Management of components: enable/disable, preview on/off, group, cluster (macro) 元件管理

## Data List (2) 資料串列之二

* Real world examples:
  * List of columns in multiple stories 柱列 + 多樓層
  * Array of circles with various radii 不同半徑的圓陣列
  * Circles on curves
  * Columns & Grilles (Shades) 柱子與格柵
* List components
* Pairing (more)

## Mapping & Conversion 數值對應與轉換

* Series, Range, Resolution, Sampling
* Linear conversion
* `Map` component

## Math Components 常用數學元件

* Max & Min
* Trigonometry functions
* And more

## Data List (3) 資料串列之三

* Compound list (data tree)
