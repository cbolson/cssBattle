# #197. Crystal

Challenge: <https://cssbattle.dev/play/197>

## Result

<table>
	<tr>
		<th width="50%">User Submission</th>
		<th width="50%">Target</th>
	</tr>
	<tr>
		<td width="50%" align="center">
			<img src="./user.png" alt="User Submission" width="100%">
		</td>
		<td width="50%" align="center">
			<img src="./target.png" alt="Target" width="100%">
		</td>
	</tr>
</table>

## Code

```html
<img><p><p><p>
<style>
img {
  position: fixed;
  border-left: dotted +53Q #f7bed9;
  z-index: 1;
  translate: 0 92px;
  padding: 30;
}
& {
  background: #5f133f;
  margin: 62 167;
}
p {
  clip-path: polygon(25px 7px, 117px 117px, 25px 227px, -67px 117px);
  height: 160;
  border-block: solid 37px #f7bed9;
  background: #f075b0;
  margin: -37 0 -234;
  + p {
    rotate: 60deg;
    + p {
      rotate: 120deg;
    }
  }
}
</style>
```

## Prettified code

```html
<img><p><p><p>
<style>
img {
  position: fixed;
  border-left: dotted +53Q #f7bed9;
  z-index: 1;
  translate: 0 92px;
  padding: 30;
}
& {
  background: #5f133f;
  margin: 62 167;
}
p {
  clip-path: polygon(25px 7px, 117px 117px, 25px 227px, -67px 117px);
  height: 160;
  border-block: solid 37px #f7bed9;
  background: #f075b0;
  margin: -37 0 -234;
  + p {
    rotate: 60deg;
    + p {
      rotate: 120deg;
    }
  }
}
</style>
```
