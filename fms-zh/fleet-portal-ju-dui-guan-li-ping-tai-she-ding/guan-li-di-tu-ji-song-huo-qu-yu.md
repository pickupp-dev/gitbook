# 管理地圖及送貨區域

{% hint style="info" %}
當商戶向車隊建立新訂單時，系統會自動為訂單分區。但每間物流公司均有自家的分區模式，即使分區名稱相同，其覆蓋範圍有可能不一樣。此文件為協助車隊經理管理地圖及送貨區域。
{% endhint %}



## 開始使用「我的送貨區域」

在車隊管理平台上建立您的第一個送貨區域前，您需要先理解縮放級別和網格級別之間的關係。這兩個因素在自定送貨區域上與詳細性及精確性方面起著十分重要的作用。



### 縮放級別

當您訪問「我的送貨區域」時，您先會看到一張世界地圖。然而，當您在地圖上放大時，它會自動聚焦到您現時處於的系統區域，包括香港、馬來西亞、新加坡和台灣。



### 網格層級

「我的送貨區域」使用正六角形的網格結構來定義送貨區域。每個正六角形單元代表地圖上的特定區域。這些單元的大小取決於網格級別，<mark style="color:red;">**範圍從1級到15級**</mark>。網格級別決定了區域的詳細程度和比例。



作為車隊經理，您可以根據自己的具體要求靈活地定義送貨區域的細節程度。通過選擇適當的網格級別，您可以確定送貨區域所需的詳細程度和精確性。<mark style="color:blue;">**較高的網格級別提供更詳細和較小的六角形單元**</mark>，而<mark style="color:purple;">**較低的網格級別則提供覆蓋範圍更廣且單元更大的區域**</mark>。



值得注意的是，區域可以互相重疊，但前提是它們屬於不同的網格級別。例如，網格第3層可以與網格第4層區域重疊，但兩個網格第3層區域不能重疊。當訂單存在於重疊區域時，系統會自動將其分配給具有更高網格級別的區域。這確保訂單被分配到更具體和詳細的區域，提高區域分配的準確性。



### 縮放級別和網格級別之間的關係

縮放級別和網格級別之間會相互影響。當您將地圖放大時，地圖會為該區域提供更多細節，因此網格級別會相對較高，其六角形單元會較小，使您能夠定義更準確的送貨區域資粒。相反，當您將地圖縮小時，地圖會顯示較大的區域且提供較少細節，因此網格級別會相對較小，其六角形單元會較大。



## 我的送貨區域概覽

<figure><img src="../.gitbook/assets/Fleet Portal User Manual Image-Chinese.drawio.png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="67">#</th><th width="234">項目</th><th>描述</th></tr></thead><tbody><tr><td>1</td><td>縮放功能</td><td>[+] : 放大地圖, [-]: 縮小地圖</td></tr><tr><td>2</td><td>地圖視窗</td><td>車隊經理可於視窗檢視已創建的送貨區域。</td></tr><tr><td>3</td><td>送貨區域</td><td>顯示送貨區域的覆蓋範圍<br><br>提示: 送貨區域的顏色跟送貨區域列表內的網格級別標題顏色是一樣的。</td></tr><tr><td>4</td><td>顯示所有區域</td><td>顯示所有網格級別上的所有送貨區域</td></tr><tr><td>5</td><td>最後發佈日期</td><td>地圖的最後發佈日期和時間</td></tr><tr><td>6</td><td>網格級別</td><td>如果「顯示所有區域」未啟用，地圖僅顯示在該網格級別下創建的區域。</td></tr><tr><td>7</td><td>已建立區域</td><td>已創建的送貨區域總數。地圖發佈前，將包括已刪除的區域。</td></tr><tr><td>8</td><td>全部展開<br>全部隱藏</td><td>全部展開: 顯示送貨區域列表內所有送貨區域;<br>全部隱藏: 隱藏送貨區域列表內所有送貨區域</td></tr><tr><td>9</td><td>送貨區域列表</td><td>顯示所有您於地圖內新增或更新的送貨區域。已刪除的區域都會於列表內出現直至地圖發佈為止。</td></tr><tr><td>10</td><td>新增送貨區域</td><td>可以在地圖上創建新的送貨區域</td></tr><tr><td>11</td><td>發佈</td><td>在最後發佈日期之後使地圖的所有更改生效，以便新訂單可以分配到新的送貨區域。</td></tr></tbody></table>



## 建立送貨區域

1.  前往「我的送貨區域」。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.48.03 PM.png" alt=""><figcaption></figcaption></figure>
2. 點擊 \[+] 放大地圖，定位您的送貨區域所在的區域。
3. 點擊「新增送貨區域」以啟動網格單元選擇器。
   1. 如果六角形單元對於送貨區域來說太大，您可以放大地圖以取得更高的網格級別，以及獲得較小的六角形單元以選擇更精確的服務範圍。
   2. 如果您想要設定較大的送貨區域，您可以縮小地圖以取得到較低的網格級別，以及獲得較大六角形單元以選擇粗略的送貨範圍。
4. 點選送貨區域的六角形單元。
   1. 當六角形單元已經點選，縮放級別將被鎖定，無法再縮放地圖直至區域被儲存為止。
   2. 您可以再次點擊六角形單元以取消單元選擇。
5.  輸入「送貨區域名稱」。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.49.43 PM.png" alt=""><figcaption></figcaption></figure>
6. 點擊「儲存」以創建區域。
   1. 區域儲存後，將建立新記錄，記錄行末將出現一個紅色圖標，表示更改尚未生效。
7.  點擊「發佈」以激活您新的送貨區域。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.50.05 PM.png" alt=""><figcaption></figcaption></figure>
8.  再次點擊「發佈」以確認發佈。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.51.14 PM.png" alt=""><figcaption></figcaption></figure>
9. 地圖的更新已生效。
   1.  地圖發佈後，區域記錄的行末將出現一個綠色圖標，表示更改已經生效。

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.51.35 PM.png" alt=""><figcaption></figcaption></figure>



## 更新送貨區域

1. 前往「我的送貨區域」。
2.  在控制面板下的送貨區域列表中，選擇您想要編輯的送貨區域。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.52.51 PM.png" alt=""><figcaption></figcaption></figure>
3. 點擊行上的「鉛筆圖標」進行區域編輯。
   1. 要更新送貨區域，您可以點選更多六角形單元以擴大送貨區域覆蓋範圍；或點選已選取的六角形單元以縮小送貨區域覆蓋範圍。
   2. 如有需要，更新送貨區區域名稱。
4. 點擊「儲存」以更新送貨區域。
   1.  區域儲存後，將建立新記錄，記錄行末將出現一個紅色圖標，表示更改尚未生效。

       <div><figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.53.06 PM.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.54.09 PM.png" alt=""><figcaption></figcaption></figure></div>
5.  點擊「發佈」以激活您的更新。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.54.28 PM.png" alt=""><figcaption></figcaption></figure>
6.  再次點擊「發佈」以確認發佈。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.54.52 PM.png" alt=""><figcaption></figcaption></figure>
7. 地圖的更新已生效。
   1.  地圖發佈後，區域記錄的行末將出現一個綠色圖標，表示更改已經生效。

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.55.14 PM.png" alt=""><figcaption></figcaption></figure>



## 刪除送貨區域

1. 前往「我的送貨區域」。
2. 在控制面板下的送貨區域列表中，選擇您想要刪除的送貨區域。
3.  點擊行上的「鉛筆圖標」進行區域編輯。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.56.02 PM.png" alt=""><figcaption></figcaption></figure>
4.  點擊行上的「垃圾桶圖標」進行區域刪除。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.56.21 PM.png" alt=""><figcaption></figcaption></figure>
5.  點擊「刪除」以確認刪除送貨區域。

    1. 確認刪除區域後，該區域記錄將被劃掉，行末也會出現一個紅色圖標，表示更改尚未生效。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.56.39 PM.png" alt=""><figcaption></figcaption></figure>
6.  點擊「發佈」以激活您的更新。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.56.50 PM.png" alt=""><figcaption></figcaption></figure>
7.  再次點擊「發佈」以確認發佈。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 at 4.57.08 PM.png" alt=""><figcaption></figcaption></figure>
8. 地圖的更新已生效。
   1. 地圖發佈後，區域記錄將會移除。
   2. 如果地圖於發佈後，沒有其他送貨區域，最後發佈日期將不將顯示。![](<../.gitbook/assets/Screenshot 2024-02-15 at 4.57.18 PM.png>)







## 問題排解

1.  在創建或編輯送貨區域時，如果在相同網格級別的附近已存在一個送貨區域，您將無法選取有關區域中的六角形單元。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 9.53.39 AM (1).png" alt=""><figcaption></figcaption></figure>
2.  在創建或編輯送貨區域時，您可以隨時啟用「顯示所有區域」功能。通過啟用此功能，您可以查看並結合其他網格級別中存在的送貨區域。這使您可以在創建或修改區域時考慮並包括來自不同網格級別的區域。

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-09 at 9.54.04 AM.png" alt=""><figcaption></figcaption></figure>

