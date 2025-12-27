<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <title>法鼓山行前確認清單</title>
  <style>
    body {
      font-family: "Noto Sans TC", Arial, sans-serif;
      background-color: #f5f5f5;
      padding: 20px;
      line-height: 1.8;
    }

    h1, h2, h3 {
      color: #3a3a3a;
    }

    .card {
      background: #ffffff;
      border-radius: 10px;
      padding: 20px;
      max-width: 800px;
      margin: 20px auto;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    ul {
      padding-left: 20px;
    }

    li {
      margin-bottom: 15px;
    }

    label {
      cursor: pointer;
    }

    input[type="checkbox"] {
      margin-right: 10px;
      transform: scale(1.2);
    }

    input[type="checkbox"]:checked + span {
      text-decoration: line-through;
      color: gray;
      opacity: 0.7;
    }

    button {
      margin-top: 15px;
      padding: 8px 16px;
      border: none;
      border-radius: 6px;
      background-color: #3a7bd5;
      color: white;
      cursor: pointer;
      font-size: 14px;
    }

    button:hover {
      background-color: #2a5cae;
    }
  </style>
</head>
<body>

<div class="card">
  <h1>法鼓山行前確認清單</h1>

  <h3>👜 袋子</h3>
  <ul>
    <li><label><input type="checkbox"><span>早課課誦單</span></label></li>
    <li><label><input type="checkbox"><span>義工背心 ×3</span></label></li>
    <li><label><input type="checkbox"><span>輕便雨衣 ×3</span></label></li>
    <li><label><input type="checkbox"><span>塑膠（垃圾）袋</span></label></li>
    <li><label><input type="checkbox"><span>醫藥箱 ×1</span></label></li>
    <li><label><input type="checkbox"><span>DVD 影片</span></label></li>
    <li><label><input type="checkbox"><span>聖號 CD</span></label></li>
  </ul>

  <h3>✉️ 大信封</h3>
  <ul>
    <li><label><input type="checkbox"><span>各車名冊</span></label></li>
    <li><label><input type="checkbox"><span>車次／車長聯絡單</span></label></li>
    <li><label><input type="checkbox"><span>車資信封</span></label></li>
    <ul>
      <li><label><input type="checkbox"><span>已標註車次</span></label></li>
      <li><label><input type="checkbox"><span>已標註車長</span></label></li>
      <li><label><input type="checkbox"><span>已標註聯絡電話</span></label></li>
    </ul>
    <li><label><input type="checkbox"><span>打齋表</span></label></li>
    <li><label><input type="checkbox"><span>筆</span></label></li>
    <li><label><input type="checkbox"><span>貼紙</span></label></li>
    <li><label><input type="checkbox"><span>夾板</span></label></li>
    <li><label><input type="checkbox"><span>便條紙</span></label></li>
    <li><label><input type="checkbox"><span>當日課程表</span></label></li>
    <li><label><input type="checkbox"><span>布達事項單</span></label></li>
  </ul>

  <h3>📦 整理箱</h3>
  <ul>
    <li><label><input type="checkbox"><span>回程藥石整理箱 ×2</span></label></li>
    <li><label><input type="checkbox"><span>紅碗 ×3</span></label></li>
    <li><label><input type="checkbox"><span>湯匙 ×3（已裝袋）</span></label></li>
    <li><label><input type="checkbox"><span>司機便當（香積室準備）</span></label></li>
  </ul>

  <h3>🪧 其他</h3>
  <ul>
    <li><label><input type="checkbox"><span>舉牌</span></label></li>
    <li><label><input type="checkbox"><span>車次條（遊覽車公司準備）</span></label></li>
  </ul>

  <h3>✅ 最終確認</h3>
  <ul>
    <li><label><input type="checkbox"><span>全數備齊</span></label></li>
    <li><label><input type="checkbox"><span>可出發</span></label></li>
  </ul>

  <button onclick="document.querySelectorAll('input[type=checkbox]').forEach(cb => cb.checked=false)">清除所有勾選</button>
</div>

</body>
</html>
