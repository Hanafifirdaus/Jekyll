---
layout: post
title:  "Javascript"
date:   2017-07-07 21:21:45 +0700
categories: jekyll update
gambar: https://www.javascript.com/images/pages/try/img-try-javascript.svg
---
[![IMAGE ALT TEXT HERE](http://constructs.stampede-design.com/wp-content/uploads/2017/01/javascriptlogo-2.jpg)](https://www.youtube.com/watch?v=XtEHrz-CCDc&list=PL6j62WXKkENrsUIguzOZIHhaVrxCTTyqv)


JavaScript adalah bahasa pemrograman web yang bersifat Client Side Programming Language. Client Side Programming Language adalah tipe bahasa pemrograman yang pemrosesannya dilakukan oleh client. Aplikasi client yang dimaksud merujuk kepada web browser seperti Google Chrome dan Mozilla Firefox.

Bahasa pemrograman Client Side berbeda dengan bahasa pemrograman Server Side seperti PHP, dimana untuk server side seluruh kode program dijalankan di sisi server.

Untuk menjalankan JavaScript, kita hanya membutuhkan aplikasi text editor dan web browser. JavaScript memiliki fitur: high-level programming language, client-side, loosely tiped dan berorientasi objek.
Berikut merupakan contoh Penggunaan Javascript dalam HTML
```
<html>
<head>
<title>Konversi waktu</title>
</head>
	<body>

	<select id="mySelect">
	  <option>DayToHour</option>
	  <option>HourToMinutes</option>
	  <option>MinutesToSeconds</option>
	  <option>HourToSeconds</option>
	</select>
	<input id="numb">
	<button type="button" onclick="time()">Hitung</button>
	
		<script>
		function time(){
			var x = document.getElementById("mySelect").selectedIndex;
			var y = document.getElementById("mySelect").options;
			var nilai, math;
			if (y[x].text == "DayToHour"){
				nilai = document.getElementById("numb").value;
				math = nilai*24;
				alert(nilai+" hari = "+math+" jam");
			}
			
			if (y[x].text == "HourToMinutes"){
				nilai = document.getElementById("numb").value;
				math = nilai*60;
				alert(nilai+" jam = "+math+" menit");
			}
			
			if (y[x].text == "MinutesToSeconds"){
				nilai = document.getElementById("numb").value;
				math = nilai*60;
				alert(nilai+" menit = "+math+" detik");
			}
			if (y[x].text == "HourToSeconds"){
				nilai = document.getElementById("numb").value;
				math = nilai*3600;
				alert(nilai+" jam = "+math+" detik");
			}
		}
		</script>
	</body>
</html>

```

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
