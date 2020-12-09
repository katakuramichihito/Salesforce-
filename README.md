<！---------------------------------------------- ------------------------->
<！-別の<META>要素を、HTMLの<HEAD>タグできますしてください。重要にありて、charset->
<！-パラメータを制限して、HTMLページの文字コードを指定してください。->
<！---------------------------------------------- ------------------------->

<META HTTP-EQUIV = "Content-type" CONTENT = "text / html; charset = UTF-8">
<script src = "https://www.google.com/recaptcha/api.js"> </ script>
<スクリプト>
関数timestamp（）{var response = document.getElementById（ "g-recaptcha-response"）; if（response == null || response.value.trim（）== ""）{var elems = JSON.parse（document.getElementsByName（ "captcha_settings"）[0] .value）; elems ["ts"] = JSON.stringify（new Date（）。getTime（））; document.getElementsByName（ "captcha_settings"）[0] .value = JSON.stringify（elems）; }} setInterval（timestamp、500）;
</ script>

<！---------------------------------------------- ------------------------->
<！-別の<FORM>かをみててください。->
<！---------------------------------------------- ------------------------->

<form action = "https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method = "POST">

<input type = hidden name = 'captcha_settings' value = '{"keyname"： "Academia2020"、 "fallback"： "true"、 "orgId"： "00D5h000000HhKe"、 "ts"： ""}'>
<input type = hidden name = "oid" value = "00D5h000000HhKe">
<input type = hidden name = "retURL" value = "http://docs.google.com/presentation/d/1oRPnhw4j3MewfQPJK9Jf4AMy4lC3az6R4as-wUeuN8c/edit#slide=id.p">

<！---------------------------------------------- ------------------------->
<！-注意：省略のパラグラフは、デバッグデバッグ用にあります。デバッグモードでテストを入力は、ありの行をコメントしててください。->
<！-<input type = "hidden" name = "debug" value = 1>->
<！-<input type = "hidden" name = "debugEmail"->
<！-value = "academiafoyk@gmail.com">->
<！---------------------------------------------- ------------------------->

<labelfor = "last_name">姓</ label> <input id = "last_name" maxlength = "80" name = "last_name" size = "20" type = "text" /> <br>

<labelfor = "country">国</ label> <inputid = "country" maxlength = "40" name = "country" size = "20" type = "text" /> <br>

<labelfor = "zip">郵便番号</ label> <inputid = "zip" maxlength = "20" name = "zip" size = "20" type = "text" /> <br>

<labelfor = "state">都道府県</ label> <input id = "state" maxlength = "20" name = "state" size = "20" type = "text" /> <br>

<labelfor = "city">市区町村</ label> <input id = "city" maxlength = "40" name = "city" size = "20" type = "text" /> <br>

<label for = "street">町名・番地</ label> <textarea name = "street"> </ textarea> <br>

<labelfor = "phone">電話</ label> <inputid = "phone" maxlength = "40" name = "phone" size = "20" type = "text" /> <br>

貴社URL：<input id = "00N5h000000yqDQ" maxlength = "255" name = "00N5h000000yqDQ" size = "20" type = "text" /> <br>

マネージャー者様（姓）：<inputid = "00N5h000000yqDV" maxlength = "20" name = "00N5h000000yqDV" size = "20" type = "text" /> <br>

招者様（名）：<inputid = "00N5h000000yqDa" maxlength = "20" name = "00N5h000000yqDa" size = "20" type = "text" /> <br>

マネージャー者様部質問：<inputid = "00N5h000000yt8L" maxlength = "40" name = "00N5h000000yt8L" size = "20" type = "text" /> <br>

<labelfor = "mobile">なし</ label> <inputid = "mobile" maxlength = "40" name = "mobile" size = "20" type = "text" /> <br>

<labelfor = "email">メール</ label> <inputid = "email" maxlength = "80" name = "email" size = "20" type = "text" /> <br>

お質問内容：<textareaid = "00N5h000000yq8A" name = "00N5h000000yq8A" rows = "6" type = "text" wrap = "soft"> </ textarea> <br>

<div class = "g-recaptcha" data-sitekey = "acialdesignkensyu"> </ div> <br>
<input type = "submit" name = "submit">

</ form>
