# Infinite Runner Code Golf
As little experiment I created an infinite runner game, trying to use less characters as possible.  
The result is a little game running in the browser, in just **510** characters.  

[Demo](http://luruke.github.io/infinite-runner-code-golf/)

```javascript
.<script>f='function(',r='Array(20).fill("-"),'.repeat(3),v='m.max(0,m.min(2,',$='m.random()';
eval(`d=document,m=Math,l=[${r}],s=0,p=1,g=1;d.onkeydown=${f}e){c=e.which;p=${v}p+(c==37?-1:(c
==39?1:0))));};j=${f}){h='<pre>';i=0;while(i++<19){h+=l[0][i]+l[1][i]+l[2][i]+"\\n";}l.forEach
(${f}k,i){k.unshift(i!=${v}m.round((${$}*2)-1)))&&${$}<.1*g?'#':'-');if(k.pop()=='#'&&i==p){al
ert(s);location.reload();}s++;});(o=[' ',' ',' '])[p]='x';d.body.innerHTML=h+o.join('');setTim
eout(j,160/(g+=.001));};j();`);</script>
```

## Features
- Keyboard binding
- Difficulty growing
- Score
- Safe lane
- Collision detection
