<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Form Tags</title>
</head>
<body>
  <form>
    <div>
      <label>
        お名前
        <input type="text">
      </label>
    </div>
    <div>
      <fieldset>
        <legend>対象の商品</legend>
        <label><input type="checkbox"> 商品A</label>
        <label><input type="checkbox"> 商品B</label>
        <label><input type="checkbox"> 商品C</label>
      </fieldset>
    </div>
    <div>
      <fieldset>
        <legend>延長保証</legend>
        <label><input type="radio" name="warranty"> 加入済</label>
        <label><input type="radio" name="warranty"> 未加入</label>
        <label><input type="radio" name="warranty"> わからない</label>
      </fieldset>
    </div>
    <div>
      <label>
        種別
        <select>
          <option>-- お問い合わせ種別を選択してください --</option>
          <option>商品が届かない</option>
          <option>商品が壊れた</option>
          <option>間違えて注文した</option>
          <option>決済手段を変えたい</option>
          <option>その他</option>
        </select>
      </label>
    </div>
    <div>
      <label>
        内容
        <textarea></textarea>
      </label>
    </div>
  </form>
</body>
</html>
