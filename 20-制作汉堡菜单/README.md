#制作汉堡菜单


知识点：nav-toggler

    参考网址： https://getbootstrap.com/docs/4.3/components/navbar/#toggler



-html---

<header>
        <div class="container">
            <nav class="navbar navbar-expand-md navbar-light">
            <a href="#" class="navbar-brand">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2">
                    <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"></path>
                    <circle cx="12" cy="13" r="4"></circle>
                </svg>
                <strong>江哥学习课程</strong>
            </a>
            <button class="navbar-toggler"  data-toggle="collapse" data-target="#navbarHeader">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div id="navbarHeader" class="collapse navbar-collapse">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link p-2" href="#" >前端课程</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link p-2" href="#" >后端课程</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link p-2" href="http://www.zhushuaijiang.com" target="_blank" >自定义表单</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link p-2" href="http://www.zhushuaijiang.com/odata/" target="_blank" >WEBPAI</a>
                    </li>
                </ul>
            </div>

            </nav>
        </div>
</header>