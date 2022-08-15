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
