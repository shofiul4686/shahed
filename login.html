<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login | ERP System</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            background: linear-gradient(135deg, #198754 0%, #0d5032 100%);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .login-card {
            width: 100%;
            max-width: 400px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            overflow: hidden;
        }
        .login-header {
            background: #f8f9fa;
            padding: 30px;
            text-align: center;
            border-bottom: 2px solid #eee;
        }
        .login-header i {
            font-size: 50px;
            color: #198754;
        }
        .card-body { padding: 30px; }
        .form-control {
            border-radius: 8px;
            padding: 12px 15px;
            border: 1px solid #ddd;
        }
        .btn-login {
            background: #198754;
            color: white;
            font-weight: bold;
            padding: 12px;
            border-radius: 8px;
            transition: 0.3s;
        }
        .btn-login:hover { background: #146c43; color: white; }
        #msg { font-size: 14px; display: none; margin-top: 15px; }
    </style>
</head>
<body>

    <div class="login-card">
        <div class="login-header">
            <i class="fas fa-user-circle"></i>
            <h4 class="mt-2 fw-bold text-dark">ERP LOGIN</h4>
        </div>
        <div class="card-body">
            <div class="mb-3">
                <label class="form-label fw-bold small">ইউজারনেম</label>
                <div class="input-group">
                    <span class="input-group-text"><i class="fas fa-user"></i></span>
                    <input type="text" id="user" class="form-control" placeholder="Admin">
                </div>
            </div>
            <div class="mb-4">
                <label class="form-label fw-bold small">পাসওয়ার্ড</label>
                <div class="input-group">
                    <span class="input-group-text"><i class="fas fa-lock"></i></span>
                    <input type="password" id="pass" class="form-control" placeholder="•••••">
                </div>
            </div>
            <button class="btn btn-login w-100" id="loginBtn" onclick="handleLogin()">
                প্রবেশ করুন <i class="fas fa-sign-in-alt ms-2"></i>
            </button>
            <div id="msg" class="alert text-center"></div>
        </div>
    </div>

    <script>
        const WEB_APP_URL = "https://script.google.com/macros/s/AKfycbzkDCX5zax-NuoSKRSxJIjL9Rx4MbtVxvm5QlrOEIxrTR-s3sVuRHJy_ISNIm3ehDYs/exec";

        function handleLogin() {
            const user = document.getElementById('user').value;
            const pass = document.getElementById('pass').value;
            const btn = document.getElementById('loginBtn');
            const msg = document.getElementById('msg');

            if(!user || !pass) {
                showMessage("সবগুলো ঘর পূরণ করুন!", "alert-danger");
                return;
            }

            btn.disabled = true;
            btn.innerHTML = '<span class="spinner-border spinner-border-sm"></span> যাচাই হচ্ছে...';

            google.script.run.withSuccessHandler(function(response) {
                if(response.status === "success") {
                    showMessage("লগইন সফল! অপেক্ষা করুন...", "alert-success");
                    // সফল হলে index পেজে রিডাইরেক্ট করবে
                    window.top.location.href = WEB_APP_URL + "?page=index";
                } else {
                    showMessage("ইউজারনেম বা পাসওয়ার্ড ভুল!", "alert-danger");
                    btn.disabled = false;
                    btn.innerHTML = 'প্রবেশ করুন <i class="fas fa-sign-in-alt ms-2"></i>';
                }
            }).checkLogin(user, pass);
        }

        function showMessage(text, type) {
            const msg = document.getElementById('msg');
            msg.innerText = text;
            msg.className = "alert text-center " + type;
            msg.style.display = 'block';
        }
    </script>
</body>
</html>
