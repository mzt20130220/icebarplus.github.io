---
layout: default
title: 文档
---

<main class="main">
    <div class="container">
        <div class="full-post">
            <h1>使用文档</h1>
            <div class="about-text">
                <h3>安装指南</h3>
                <p>IceBarPlus 支持 Microsoft Edge 浏览器，您可以通过以下方式安装：</p>
                <ol>
                    <li>从 GitHub Releases 页面下载最新的 `dist.crx` 文件</li>
                    <li>打开 Edge 浏览器，访问 `edge://extensions/`</li>
                    <li>开启右上角的"开发人员模式"开关</li>
                    <li>将 `dist.crx` 文件拖入扩展页面</li>
                    <li>在弹出的确认对话框中点击"添加扩展"</li>
                </ol>
                
                <h3>快速开始</h3>
                <p>安装完成后，您可以点击浏览器工具栏中的 IceBarPlus 图标打开扩展界面。</p>
                
                <h3>功能模块</h3>
                
                <h4>HTTP请求测试器</h4>
                <p>支持所有常见的HTTP方法（GET、POST、PUT、DELETE等），您可以：</p>
                <ul>
                    <li>配置请求URL</li>
                    <li>添加自定义请求头</li>
                    <li>设置请求体内容</li>
                    <li>查看响应结果</li>
                </ul>
                
                <h4>SQL注入检测</h4>
                <p>自动测试常见的SQL注入漏洞，包括：</p>
                <ul>
                    <li>布尔盲注</li>
                    <li>时间盲注</li>
                    <li>报错注入</li>
                    <li>联合查询注入</li>
                </ul>
                
                <h4>XSS漏洞测试</h4>
                <p>提供预设的XSS payload库，支持：</p>
                <ul>
                    <li>反射型XSS测试</li>
                    <li>存储型XSS测试</li>
                    <li>DOM型XSS测试</li>
                </ul>
                
                <h4>CSRF令牌分析</h4>
                <p>自动检测和分析页面中的CSRF令牌：</p>
                <ul>
                    <li>提取表单中的CSRF令牌</li>
                    <li>分析令牌的随机性</li>
                    <li>检查令牌的验证机制</li>
                </ul>
                
                <h4>请求重放</h4>
                <p>记录您的请求历史，支持：</p>
                <ul>
                    <li>查看历史请求记录</li>
                    <li>一键重发请求</li>
                    <li>修改请求后重发</li>
                </ul>
                
                <h4>响应头分析器</h4>
                <p>检查HTTP响应头的安全配置：</p>
                <ul>
                    <li>检测CSP配置</li>
                    <li>检查XSS保护头</li>
                    <li>验证HSTS设置</li>
                </ul>
                
                <h4>代理设置</h4>
                <p>快速配置浏览器代理：</p>
                <ul>
                    <li>预设Burp Suite配置</li>
                    <li>预设ZAP配置</li>
                    <li>自定义代理设置</li>
                </ul>
                
                <h3>常见问题</h3>
                
                <h4>扩展无法加载？</h4>
                <p>请确保您已经开启了"开发人员模式"，并且使用的是最新版本的Edge浏览器。</p>
                
                <h4>如何更新扩展？</h4>
                <p>下载最新版本的 `dist.crx` 文件，然后重新安装即可。</p>
                
                <h4>发现了bug？</h4>
                <p>欢迎在 <a href="https://github.com/mzt20130220/mzt20130220.github.io/issues" target="_blank" rel="noopener noreferrer">GitHub Issues</a> 中报告，我们会尽快修复。</p>
            </div>
        </div>
    </div>
</main>
