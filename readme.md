# 各api使用手測

## **resumenew.json**

json layout => Resumenews
<br>

```typescript
type Resumenew = {
  id: string;
  name: string;
  page: string;
  useSkill: srting[],
  img: string;
  spr: string;
}
type Resumenews = resumenew []

```

### 欄位解釋
* id : 唯一識別 
* name : 名稱 
* page : 部署網址或repo位置 
* useSkill : 此頁面使用lib or framework 
* img : 圖片放置位置 (*註一) 
* spr : 頁面描述

註一 : img repo位置: "https://eddie605134.github.io/CollectionPage/"

-------------------------------------------------------
## **skiill_list**
skiill_list

## **英文單字**
english_word

國高中英文單字json

### resource: 
-  [192 利用國中1200 和高中7000 的英文單字 JSON 開發單字 App](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84%E8%A9%A6%E7%85%89-%E5%8B%87%E8%80%85%E7%9A%84-100-%E9%81%93-swift-ios-app-%E8%AC%8E%E9%A1%8C/%E5%88%A9%E7%94%A8%E5%9C%8B%E4%B8%AD1200-%E5%92%8C%E9%AB%98%E4%B8%AD7000-%E7%9A%84%E8%8B%B1%E6%96%87%E5%96%AE%E5%AD%97-json-%E9%96%8B%E7%99%BC%E5%96%AE%E5%AD%97-app-bdeb3c87c087)
- [剛明高中學習資源](http://www.kmsh.tn.edu.tw/~edu92/kmedu100/sub6-7.htm)