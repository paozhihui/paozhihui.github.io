---
layout: home
title: 联系我
---

<div class="contact-form">
    <h2>联系我</h2>
    <form action="#" method="post">
        <div class="form-group">
            <label for="name">姓名</label>
            <input type="text" id="name" name="name" placeholder="请输入您的姓名" required>
        </div>
        <div class="form-group">
            <label for="email">邮箱</label>
            <input type="email" id="email" name="email" placeholder="请输入您的邮箱" required>
        </div>
        <div class="form-group">
            <label for="subject">主题</label>
            <input type="text" id="subject" name="subject" placeholder="请输入消息主题" required>
        </div>
        <div class="form-group">
            <label for="message">消息内容</label>
            <textarea id="message" name="message" placeholder="请输入您想说的话..." required></textarea>
        </div>
        <button type="submit" class="btn-submit">发送消息</button>
    </form>
</div>