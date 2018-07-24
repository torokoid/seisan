# seisan

  <section>
 <h2>簡易表計算-JavaScriptバージョンアップ版</h2>
  <script>
//各自の支払額を保存
var numsu = prompt ("ス～さんの支払額は？");
var numsi = prompt ("シ～さんの支払額は？");
var numha = prompt ("ハ～さんの支払額は？");
var nummu = prompt ("ム～さんの支払額は？");
//各自の会計額を計算
var goukei = Math.round (Number(numsu) + Number(numsi) + Number(numha) + Number(nummu));
//各自の割り勘分を計算
var buntan = Math.round (goukei/4)
var warisu = Math.round (Number(buntan) - Number(numsu))
var warisi = Math.round (Number(buntan) - Number(numsi))
var wariha = Math.round (Number(buntan) - Number(numha))
var warimu = Math.round (Number(buntan) - Number(nummu))
//計算結果を表示
//alert ("合計金額は" + goukei + "円です");
//alert ("スーさんの清算は" + warisu + "円です");
//alert ("シーさんの清算は" + warisi + "円です");
//alert ("ハーさんの清算は" + wariha + "円です");
//alert ("ムーさんの清算は" + warimu + "円です");

document.write ("支出 <br> スーさん：" + numsu + "円 <br> シーさん：" + numsi + "円 <br> ハーさん：" + numha + "円 <br> ムーさん：" + nummu + "円 <br> 合計金額" + goukei + "円 <br><br> 各自の清算 <br> スーさん：" + warisu + "円 <br> シーさん：" + warisi + "円 <br> ハーさん：" + wariha + "円 <br> ムーさん：" + warimu + "円 <br><br> 以上、お帰りも気を付けて、来年も元気に再開～(^^)/");
</script>
 </section>
