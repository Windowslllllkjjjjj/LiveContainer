<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF8">
    <title>评论功能示例</title>
</head>
<body>
    <h1>评论区</h1>
    <form action="submit_comment.php" method="post">
        <label for="username">用户名：</label>
        <input type="text" id="username" name="username" required><br>
        <label for="email">邮箱：</label>
        <input type="email" id="email" name="email" required><br>
        <label for="comment">评论内容：</label>
        <textarea id="comment" name="comment" rows="4" cols="50" required></textarea><br>
        <input type="submit" value="提交评论">
    </form>
    <h2>已有评论</h2>
    <table border="1">
        <tr>
            <th>用户名</th>
            <th>邮箱</th>
            <th>评论内容</th>
        </tr>
        <!在这里插入从数据库获取的评论数据 >
    </table>
</body>
</html>
