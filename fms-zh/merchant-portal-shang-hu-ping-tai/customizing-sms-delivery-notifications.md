---
description: 您可以建立和管理可自訂的簡訊通知，在交貨過程的不同階段向收件人或其他特定聯絡人發送簡訊。
---

# 客製化簡訊模板

## 建立簡訊模板

1. 登入商戶平台。
2. 點選左方的「帳戶」-> 「用戶」按鈕。
3. 點選「 電子郵件及簡訊模板」 介面。
4.  點選「+」按鈕以建立新的簡訊模板。\


    <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
5. 您可以在以下表格輸入簡訊的資料。

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

以下是表格中每項資料的簡介：

<table><thead><tr><th width="181.33333333333331">項目</th><th width="146">可選項目</th><th>簡介</th></tr></thead><tbody><tr><td>模版標題</td><td></td><td>這是您所建立的模版標題。</td></tr><tr><td>通知方式</td><td></td><td>點選「短訊」。</td></tr><tr><td>觸發於</td><td><p>送達後</p><p>取件完成後</p><p>接單後 </p></td><td><p></p><p>選擇簡訊發送的時機：</p><ul><li>送達後 - 信息將於訂單狀態為「送達後」送出。</li><li>取件完成後 - 信息將於訂單狀態為「取件完成後」送出。</li><li>接單後 - 信息將於訂單狀態為「接單後」送出。</li></ul></td></tr><tr><td>傳送於</td><td><p>額外聯絡人 1 </p><p>額外聯絡人 2<br>寄件者<br>收件者</p></td><td><p>選擇簡訊發送的收件者：</p><ul><li>額外聯絡人 1 - 這是在<a href="creating-and-managing-orders.md#shi-yong-csv-pi-liang-chuang-jian-ding-chan">車隊配送範本</a>中的可選項目：額外聯絡人下的聯絡人A。</li><li>額外聯絡人 2 - 這是在<a href="creating-and-managing-orders.md#shi-yong-csv-pi-liang-chuang-jian-ding-chan">車隊配送範本</a>中的可選項目：額外聯絡人下的聯絡人B。 </li><li>寄件者 - 訂單的寄件者。</li><li>收件者 - 訂單的收件者。</li></ul></td></tr><tr><td>狀態</td><td><p>停用</p><p>啟用</p></td><td><p></p><p>選擇您的簡訊狀態：</p><ul><li>啟用： 如您需要發送此簡訊，請確保狀態為「啟用」。</li><li>停用: 如您不再需要發送此簡訊，請確保狀態為「停用」。</li></ul></td></tr><tr><td>信息</td><td></td><td><p>這將是您的簡訊內容。您可以包括相關的訂單資料，例如：</p><ol><li>寄件者信息</li><li>收件者信息 </li><li>訂單信息</li></ol><p>要插入這些信息，將滑鼠光標放在您希望相關細節出現的位置，並從（1），（2）或（3）中選擇不同的項目。它將以{{xxxx}}的形式出現在內容區域。當系統發送短信通知時，此占位符將自動被實際的訂單明細替換。<br><br>如要在簡訊內容中開新一行，只需在您希望換行的位置輸入「\n」。</p></td></tr></tbody></table>



6.  當您輸入簡訊所需的資料後，請按「更新」按鈕以完成並儲存簡訊模板。\


    <figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

\
請留意，簡訊無法自動切換到其他語言。如有必要，您可以在一條簡訊中同時以中文和英文發送。請注意，實際的簡訊字數可能會超過一條簡訊的字數上限。

## 問題排解

1. 我未能使用「更新」按鈕。
   * 這可能是因為您的簡訊數量已達到最高的五條上限。請考慮減少簡訊內容的長度或將其分為多個簡訊。
2. 接收者未能收到簡訊。
   * 檢查模板的狀態，並確保它們被設置為「啟用」。另外，請同時確認接收者的聯絡資料是準確無誤。
