# LOVE ONE LINE
###### LOC in git repo
git ls-files | xargs cat | wc -l

###### JS shortener
0|123.56464
123

0|"123"
123

1e3
1000

var a = 0
if(!a) { console.log("sıfır") }
a||console.log("sıfır")

!0
true

!1
false

document.getElementById('a').innerHTML = "foo";
a.innerHTML = "foo";

Math.floor(Math.random()*10)
0|Math.random()*10

Math.round(a)
a+.5|0

A*Math.pow(2,B)
A<<B


###### POSTMAN
Auto set token to postman global variable

```postman.setGlobalVariable("auth", JSON.parse(responseBody).data.token.accessToken);```
