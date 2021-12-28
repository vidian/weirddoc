# Cara Install

Install seperti biasa, sama seperti yang ada di panduan website [vuepress](https://vuepress.vuejs.org/guide/getting-started.html).

## Sebelum Install dan Sesudah Install

<p style="text-align:justify;">Sebelum install yang diperlukan hanya install node.js dan npm. Setelah itu baru install vuepress. Dan sesudah install ya tinggal baca documentationnya atau nonton tutorial di youtube untuk generate static pagenya. </p>

![An image](/images/milky.jpg)

## Issue Hot Reload

Ada issue hot reload di beberapa user vuepress, solusinya bisa menambahkan `--temp .temp` pada package.json di bagian scripts.
Seperti ini.
```json
{
  "scripts": {    
    "docs:dev": "vuepress dev docs --temp .temp",    
  },
}
```

## Perbandingan Vuepress dengan Readthedocs

<p style="text-align: justify;">Perbandingannya jelas lebih keren pake vupress, tampilan lebih menarik, modern, dan simple, Readthedocs sangat kompleks dan ribet menurutku haha. Sebenernya karena Vuepress ini lebih keren karena Vue-nya itu sendiri, apalagi bagi yang terbiasa javascript.<br>
Dua kalimat diatas itu basa - basi, alasan jujurnya karena Vuepress itu Vue.js, jadi keren wkwk dan Readthedocs memang ribet. (Well lebih kompleks aja sih)</p>
