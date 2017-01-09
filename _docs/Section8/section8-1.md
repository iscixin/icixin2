---
title: 補充 - 資料交換的格式
category: Section8
order: 0
---

## XML
```xml
<?xml version="1.0"?>
<?xml-stylesheet href="catalog.xsl" type="text/xsl"?>
<!DOCTYPE catalog SYSTEM "catalog.dtd">
<catalog>
   <product description="Cardigan Sweater" product_image="cardigan.jpg">
      <catalog_item gender="Men's">
         <item_number>QWZ5671</item_number>
         <price>39.95</price>
         <size description="Medium">
            <color_swatch image="red_cardigan.jpg">Red</color_swatch>
            <color_swatch image="burgundy_cardigan.jpg">Burgundy</color_swatch>
         </size>
         <size description="Large">
            <color_swatch image="red_cardigan.jpg">Red</color_swatch>
            <color_swatch image="burgundy_cardigan.jpg">Burgundy</color_swatch>
         </size>
      </catalog_item>
      <catalog_item gender="Women's">
         <item_number>RRX9856</item_number>
         <price>42.50</price>
         <size description="Small">
            <color_swatch image="red_cardigan.jpg">Red</color_swatch>
            <color_swatch image="navy_cardigan.jpg">Navy</color_swatch>
            <color_swatch image="burgundy_cardigan.jpg">Burgundy</color_swatch>
         </size>
         <size description="Medium">
            <color_swatch image="red_cardigan.jpg">Red</color_swatch>
            <color_swatch image="navy_cardigan.jpg">Navy</color_swatch>
            <color_swatch image="burgundy_cardigan.jpg">Burgundy</color_swatch>
            <color_swatch image="black_cardigan.jpg">Black</color_swatch>
         </size>
         <size description="Large">
            <color_swatch image="navy_cardigan.jpg">Navy</color_swatch>
            <color_swatch image="black_cardigan.jpg">Black</color_swatch>
         </size>
         <size description="Extra Large">
            <color_swatch image="burgundy_cardigan.jpg">Burgundy</color_swatch>
            <color_swatch image="black_cardigan.jpg">Black</color_swatch>
         </size>
      </catalog_item>
   </product>
</catalog>
```

---

## JSON
JavaScript Object Notation

```json
{
 "subject": "Math",
 "score":80
}
```

---

### Ballr (Written in R lang)

[GitHub SourceCode](https://github.com/toddwschneider/ballr)
![Ballr](/icixin/images/lessons/ballr.png)
![Ballr Json](/icixin/images/lessons/ballr-json.png)

## R lang 自學資源
+ [GTWang: R 教學](https://blog.gtwang.org/programming/r/)
+ [R 也能互動！用 Shiny 與 R 語言將你的數據變成互動圖表](http://blog.infographics.tw/2016/04/interactive-r-with-shiny/)
+ [The R Project for Statistical Computing](https://www.r-project.org/)
+ [RStudio IDE](https://www.rstudio.com/)
+ [Shiny by RStudio](https://shiny.rstudio.com/)
+ [R Basic](https://joe11051105.gitbooks.io/r_basic/content/)