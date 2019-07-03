#制作提示框
    tooltip
================
    #知识点
    * data-toggle="tooltip"
    * data-placement    显示位置设置

    #实战演习


  <div class="tab-content py-5">
      <div id="Nodejs" class="tab-pane active">
          <p>Node.js是一个 <span class="font-weight-bold text-danger"  title="运行时runtime" data-toggle="tooltip1" data-placement="top"> Javascript运行环境(runtime)</span>，发布于2009年5月，
              <span class="font-weight-bold text-warning" title="目前是 Google Brain的一个软件工程师,他是 Node.js 之父" data-toggle="tooltip"> 由Ryan Dahl开发</span>由Ryan Dahl开发，实质是对Chrome V8引擎进行了封装。</p>
      </div>
      <div id="c#" class="tab-pane">
          <p>C# 是一个简单的、现代的、通用的、面向对象的编程语言，它是由微软（Microsoft）开发的。</p>
      </div>
  </div>

    <script src="../lib/bootstrap-4.3.1-dist/others/jquery-3.3.1.slim.min.js"></script>
    <script src="../lib/bootstrap-4.3.1-dist/others/popper.min.js"></script>
    <script src="../lib/bootstrap-4.3.1-dist/js/bootstrap.js"></script>
      <script>
          $(function () {
              'use strict';
             $('[data-toggle="tooltip1"]').tooltip();
          })
      </script>
