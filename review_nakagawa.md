# Bolt PC
## 最終レビューの修正内容
----------
### ---HTML---
#### 1. divタグ消し忘れ
 - aタグをdivで囲って付けていたスタイルを全てaタグに移動した際のdivの消し忘れがあったため削除しました（対象: Contactボタン、Emailボタン）

### ---CSS---
#### 2. headerの下に入り込む部分の余白に関して
- headerの下に入り込む分の余白がmainでなくtheme部分に付いていたため、mainにpadding-topを指定しました。
- また、hederの高さ70pxに対し、padding-top:75pxとなっていたため、70pxに訂正しました。

#### 3. css書き順
- 「共通部分」のマークアップの順番を、タグ自体(body等)への指定＞classへの指定になるよう並べ替えしました。

#### 4. px消し忘れ
- margin-top: 0px; の ”px”を削除しました。

#### 5. Our Skills部分のwidth指定の削除
- 下記の削除、追加をしました。
```css
.skills-inner {
  padding: 70px 0 100px 0;
  color: #fff;
  width: 1028px;/* ←削除 */
  text-align: center;
}

.skills__img_box {
  justify-content: center;/* ←追加 */
  margin-top: 40px;
}
```





