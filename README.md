# JavaScript30
30 Day 練習，來自： Vanilla JS Challenge https://JavaScript30.com

# Ch01 - JavaScriptDrumKit 
<a href="https://yes123430.github.io/JavaScript30/01_JavaScriptDrumKit/index-START.html">DEMO</a>
1. 透過按下鍵盤來撥放音樂
2. 參考KeyCode、document.querySelector('object')、play()、data-* 定義觀念、window.addEventListener

# Ch02 - JS and CSS Clock
<a href="https://yes123430.github.io/JavaScript30/02_JSandCSSClock/index-START.html">DEMO</a>
1. 一個圓圈360度、transform -> 可以實作DOM 旋轉、傾斜、縮放
 ```css
    
    .hand {
      width: 50%;
      height: 6px;
      background: black;
      position: absolute;
      top: 50%;

      transform-origin: 100%;   //設置物件定點位置
      transform: rotate(90deg); //rotate(xxdeg)旋轉
      transition: all 0.05s;    // all(所有元素) 動畫幾秒
    }
 ```
2. setInvterval(方法,多少時間執行一次單位毫秒)
3. setTimeout(方法,延遲多久''只''執行一次)
4. window.requestAnimationFrame(方法) -> 主要依據畫面XXhz去更新
通知瀏覽器我們想要產生動畫，並且要求瀏覽器在刷新畫面前呼叫特定函數刷新動畫；這個方法接受一個函數(回撥函數, Callback)，然後該函數會被呼叫執行以刷新繪圖。

複雜的動畫採取 : requestAnimationFrame

# Ch03 - CSS Variables

