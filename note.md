## テーブルをExcel風に変更

16の空セルにも罫線を付ける
index.thml
```
<tr>
  <td class="section-title">【建物（定額】</td>
  <td></td><td></td><td></td><td></td><td></td><td></td><td></td>
  <td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td>
</tr>

```

style.css
```
table {
    border-collapse: collapse;
    width: 100%;
}

th, td {
    border: 1px solid #000; /* 全部のセルに縦横の罫線 */
    padding: 8px;
    text-align: left;
    background-color: #fff;
}
```

