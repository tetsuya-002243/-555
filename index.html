<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>橋梁点検 写真野帳 v2</title>
  <link rel="manifest" href="manifest.json" />
  <link rel="stylesheet" href="style.css?v=2" />
</head>
<body>
  <header>
    <div>
      <h1>橋梁点検 写真野帳 v2</h1>
      <p>PDF損傷図をタップ → 自動採番 → 写真撮影 → CSV / ZIP出力</p>
    </div>
    <div class="header-actions">
      <button id="btnSaveLocal" type="button">一時保存</button>
      <button id="btnLoadLocal" type="button">復元</button>
      <button id="btnClear" type="button" class="danger">全削除</button>
    </div>
  </header>

  <main>
    <section id="statusBox" class="status ok">読込状態：初期化中</section>

    <section class="panel">
      <h2>1. 案件情報</h2>
      <div class="grid">
        <label>橋梁名<input id="bridgeName" type="text" placeholder="例：○○橋" /></label>
        <label>路線名<input id="routeName" type="text" placeholder="例：市道○○線" /></label>
        <label>点検日<input id="inspectionDate" type="date" /></label>
        <label>点検者<input id="inspector" type="text" placeholder="例：中川" /></label>
      </div>
    </section>

    <section class="panel sticky">
      <h2>2. 操作</h2>
      <div class="toolbar">
        <label class="fileBtn">PDF損傷図を開く<input id="pdfInput" type="file" accept="application/pdf" /></label>
        <button id="btnPrev" type="button">前ページ</button>
        <span id="pageInfo" class="badge">PDF未読込</span>
        <button id="btnNext" type="button">次ページ</button>
        <button id="btnFit" type="button">全体表示</button>
        <button id="btnPhotoMode" type="button" class="primary">写真モード</button>
        <button id="btnMoveMode" type="button">移動モード</button>
        <button id="btnExportCsv" type="button">CSV出力</button>
        <button id="btnExportZip" type="button">写真ZIP出力</button>
      </div>
      <p class="hint">写真モード：損傷位置をタップすると 001, 002... が自動発番され、続けてカメラ/写真選択が開きます。</p>
    </section>

    <section class="panel">
      <h2>3. 損傷図</h2>
      <div id="viewer">
        <div id="stage">
          <canvas id="pdfCanvas"></canvas>
          <div id="markerLayer"></div>
        </div>
        <div id="emptyMessage">PDF損傷図を読み込んでください</div>
      </div>
      <input id="cameraInput" class="hidden" type="file" accept="image/*" capture="environment" />
    </section>

    <section class="panel">
      <h2>4. 選択中の写真記録</h2>
      <div id="selectedInfo" class="selected">未選択</div>
      <div class="grid">
        <label>損傷名・部材名<input id="damageTitle" type="text" placeholder="例：床版ひびわれ、主桁腐食" /></label>
        <label>備考<input id="note" type="text" placeholder="例：幅0.2mm、L=300mm" /></label>
      </div>
      <div class="toolbar">
        <button id="btnUpdateRecord" type="button">記録更新</button>
        <button id="btnRetake" type="button">写真を撮り直す/添付</button>
        <button id="btnDeleteRecord" type="button" class="danger">選択記録を削除</button>
      </div>
      <div id="photoPreview" class="preview"></div>
    </section>

    <section class="panel">
      <h2>5. 記録一覧</h2>
      <div id="recordList" class="recordList"></div>
    </section>
  </main>

  <footer>
    <p>注意：実際の点検PDF・写真・CSV・ZIPはGitHubへ登録せず、端末または社内のOneDrive/SharePoint等で管理してください。</p>
  </footer>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js"></script>
  <script src="app.js?v=2"></script>
</body>
</html>
