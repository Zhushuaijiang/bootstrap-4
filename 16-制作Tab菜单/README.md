#制作Tab菜单
    #制作Tab菜单内容布局+完善
    知识点：
        nav
        nav-item
        nav-link
        tab-content
        tab-pane
        data-toggle="tab"
    参考网址
            https://getbootstrap.com/docs/4.3/components/navs/

     ##实战演习

   <section class="py-5">
       <h2 class="text-center">我爱编程-Tab菜单</h2>
        <div class="container">
            <ul class="nav nav-tabs">
                <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#java">java</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#dotnet">dotnet</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python">python</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#nodejs">nodejs</a></li>
            </ul>
            <div class="tab-content py-3">
                <div class="tab-pane active" id="java">我爱java</div>
                <div class="tab-pane" id="dotnet">dotnet</div>
                <div class="tab-pane" id="python">我爱python</div>
                <div class="tab-pane" id="nodejs">我爱nodejs</div>
            </div>

        </div>
   </section>
