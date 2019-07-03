#元padding 和 marging
    ##知识点

    *  [p|m][location]-[size]


       参考网址
          https://getbootstrap.com/docs/4.3/utilities/spacing/

      *** 用法说明

      p:pading
      m:margin

      location:
       - t b l r
        t:top
        b:bottom
        l:left
        r:right

       - x,y
        -x:lr
        -y:tb

      size
      - 1:0.25em
      - 2:0.5em
      - 3:1.0em
      - 4:1.5em
      - 5:3.0em
      - auto

      em: 相对长度单位，这个单位表示元素的font-size的计算值。如果用在font-size 属性本身，它会继承父元素的font-size。
      rem：以根要素为基准，按照比例设定子元素的大小

      参考网页：
       https://developer.mozilla.org/zh-CN/docs/Web/CSS/length


    ## 实战演习

        <style>
                    .my-container{
                        width: 200px;
                        height: 200px;

                        background: #dddddd;
                        margin-bottom: 5px;
                        border: 1px solid #000;
                    }
                </style>

        <div class="my-container pt-3 pl-3 mt-1">
            <div class="bg-primary w-25 h-25 pt-1 pl-2">padding和margin的使用</div>
        </div>
        <div class="my-container pt-3 pl-3">
            <div class="bg-primary w-75 h-100">padding和margin的使用</div>
        </div>

