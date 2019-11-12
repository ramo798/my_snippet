# HTML/CSS common

### css レスポンシブ ブレイクポイント
```
@media screen and (max-width:1024px){  
}  
@media screen and (max-width:768px){  
}  
@media screen and (max-width:480px){  
}  
@media screen and (max-width:375px){  
}
```

### display:grid スニペット
```
.oya{  
display: grid;  
grid-template-columns: repeat(3, 1fr);  
grid-auto-rows: 1fr; 
grid-gap: 15px;  
}
.ko{

}
```

### 要素上下左右中央配置
```
.youso{
display: flex;  
align-items: center;  
justify-content: center;
}
```

###　擬似要素でh1の横に縦ボーダー出すやつ
```
h1:before{
    position: absolute;
    content: '';
    left: -5px;
    border: 1.5px solid #ff6f11;
    /* どちらか使える　*/
    /* border-left: solid 5px #7db4e6; */ 
    height: 20px;
    top: 0;
    bottom: 0;
    margin: auto;
    border-radius: 15px;
}

```

### memo
```
padding margin は極力％で  
  
レスポンシブで制御する時、中の要素の周りに
max wdth 1090px  
margin 0 auto  
padding 3%  
  
box-sizing  
boderbox  
使っていく  
box-sizing: border-box;

上下真ん中のとき
親がvhなら
min px指定して　height を　vhでいれる

```
