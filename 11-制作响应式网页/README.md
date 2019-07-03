# 制作响应式网页
    知识点：
        1：col-*
        2：col-sm-*
        3：col-md-*
        4：col-lg-*
        5：col-xl-*
    参考网页：
          https://getbootstrap.com/docs/4.3/layout/grid

     --html-------------

  <div class="row mb-3">
      <div class="col-6 bg-success">Hello</div>
  </div>
  <div class="row mb-3">
      <div class="col-xl-12 col-lg-10 col-md-8 col-sm-4 col-6 bg-warning">hello2</div>
  </div>
  <div class="row">
      <div class="col-12 col-md-6 bg-danger">hello3</div>
      <div class="col-12 col-md-6 bg-primary">hello4</div>
  </div>
  <div class="row">
      <div class="col-12 col-md-6 bg-danger">hello5</div>
      <div class="d-none d-md-block col-md-6 bg-primary">hello6</div>
  </div>