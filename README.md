# edit-distance
基于动态规划的字符串最短编辑距离问题实现

## 用法

```javascript
	var str1 = 'aaas';
	var str2 = 'a';

	var newStr = patch(str1, str2);

	console.log(newStr, newStr === str2);
```