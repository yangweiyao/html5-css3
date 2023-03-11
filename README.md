# html5-css3
记录学习html5+css3案例教程

<h5>综合案例</h5><br>
<img width="871" alt="image" src="https://user-images.githubusercontent.com/67896996/224490463-a097ea13-2a05-46b0-b789-265bbb364561.png">

```
  /* 1. 渐变背景的盒子 */
  .box .mask {
      position: absolute;
      left: 0;
      top: 0;
      width: 350px;
      height: 247px;
      background-image: linear-gradient(
          transparent,
          rgba(0,0,0,.6)
      );
      opacity: 0;
      transition: all .5s;
  }

  /* 2. hover效果 */
  /* 2.1 图片缩放 */
  .box li .pic img {
      transition: all .5s;
  }
  .box li:hover .pic img {
      transform: scale(1.2);
  }


  /* 2.2 渐变背景显示 */
  .box li:hover .mask {
      opacity: 1;
  }

  /* 2.3 文字向上移动 */
  .box li:hover .txt {
      transform: translateY(-50px);
  }
```

<img width="864" alt="image" src="https://user-images.githubusercontent.com/67896996/224490469-d69ba1e3-1bc6-450f-b54a-f5d9b6b32872.png">
