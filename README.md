# ton
<DIV STYLE="width: 120px; height: 50px; border: 1px solid blue;overflow: hidden; text-

overflow:ellipsis"> 

<NOBR>就是比如有一行文字，很长，表格内一行显示不下.</NOBR> 

</DIV>
<script> 

self.moveTo(0,0) 

self.resizeTo(screen.availWidth,screen.availHeight) 

</script> 

<div style="width:300px;padding:20px;overflow:hidden;word-wrap:break-word;word-

break:break:all; font-size:12px; line-height:18px; background-color:#eeeeee;">

<font disabled>

怎么样，我凹下去了吧？<br>

你不想试试吗？<br>

<a href="xxxx.com/">xxxx.com</a></font>

</div>

<script>

function Preview()

{var TestWin=open('');

TestWin.document.write(code.value);}

</script>

<textarea id=code cols=60 rows=15></textarea>

<br>

<button onclick=Preview() >运行</button>
