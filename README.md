# Malik-fiaz-MD-
Malik fiaz dark hacker 
<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malik Fiaz MD - WhatsApp Bot Pairing Dashboard</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --bg-color: #0b0f19;
            --card-bg: #111827;
            --accent-green: #22c55e;
            --accent-glow: rgba(34, 197, 94, 0.3);
            --text-main: #f9fafb;
            --text-muted: #9ca3af;
            --border-color: #1f2937;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 500px;
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 20px;
            padding: 30px 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
            text-align: center;
            margin-top: 20px;
        }

        .bot-avatar {
            width: 90px;
            height: 90px;
            background: linear-gradient(135deg, #22c55e, #166534);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 40px;
            color: white;
            box-shadow: 0 0 20px var(--accent-glow);
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 0 0 0 var(--accent-glow); }
            70% { transform: scale(1.05); box-shadow: 0 0 0 15px rgba(34, 197, 94, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(34, 197, 94, 0); }
        }

        h1 {
            font-size: 26px;
            font-weight: 900;
            margin-bottom: 5px;
            color: var(--text-main);
        }

        .owner-tag {
            font-size: 14px;
            color: var(--accent-green);
            background: rgba(34, 197, 94, 0.1);
            padding: 4px 12px;
            border-radius: 20px;
            display: inline-block;
            margin-bottom: 20px;
            font-weight: 500;
        }

        p.desc {
            font-size: 14px;
            color: var(--text-muted);
            margin-bottom: 25px;
            line-height: 1.6;
        }

        .input-group {
            position: relative;
            margin-bottom: 20px;
            text-align: right;
        }

        .input-group label {
            display: block;
            font-size: 13px;
            color: var(--text-muted);
            margin-bottom: 8px;
        }

        .input-box {
            display: flex;
            background: var(--bg-color);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            overflow: hidden;
            transition: 0.3s;
        }

        .input-box:focus-within {
            border-color: var(--accent-green);
            box-shadow: 0 0 10px var(--accent-glow);
        }

        .input-box span {
            background: rgba(255, 255, 255, 0.05);
            padding: 14px 16px;
            color: var(--text-muted);
            font-size: 16px;
            border-left: 1px solid var(--border-color);
        }

        .input-box input {
            flex: 1;
            background: transparent;
            border: none;
            outline: none;
            color: white;
            font-size: 16px;
            padding: 0 15px;
            text-align: left;
            direction: ltr;
        }

        .btn-submit {
            width: 100%;
            background: var(--accent-green);
            color: #0b0f19;
            border: none;
            padding: 14px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 700;
            cursor: pointer;
            transition: 0.3s;
            box-shadow: 0 4px 15px var(--accent-glow);
        }

        .btn-submit:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }

        .result-box {
            margin-top: 20px;
            background: var(--bg-color);
            border: 1px dashed var(--accent-green);
            padding: 15px;
            border-radius: 12px;
            display: none;
        }

        .code-display {
            font-size: 24px;
            font-weight: 900;
            color: var(--accent-green);
            letter-spacing: 2px;
            margin: 10px 0;
            direction: ltr;
        }

        .instructions {
            margin-top: 30px;
            text-align: right;
            background: rgba(255, 255, 255, 0.02);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 15px;
        }

        .instructions h3 {
            font-size: 15px;
            margin-bottom: 10px;
            color: var(--text-main);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .instructions ol {
            padding-right: 20px;
            font-size: 13px;
            color: var(--text-muted);
            line-height: 1.8;
        }

        .footer {
            margin-top: 30px;
            font-size: 13px;
            color: var(--text-muted);
            text-align: center;
        }

        .footer a {
            color: var(--accent-green);
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="bot-avatar">
            <i class="fa-solid fa-robot"></i>
        </div>
        <h1>Malik Fiaz MD</h1>
        <div class="owner-tag"><i class="fa-solid fa-crown"></i> اونر: ملک فیاض (+923221027802)</div>
        <p class="desc">واٹس ایپ کا بہترین اور تیز ترین بوٹ۔ اپنا نمبر درج کریں اور سیکنڈوں میں پیئرنگ کوڈ حاصل کریں۔</p>

        <div class="input-group">
            <label>اپنا واٹس ایپ نمبر درج کریں (بغیر + کے):</label>
            <div class="input-box">
                <input type="tel" id="whatsappNumber" placeholder="923221027802">
                <span><i class="fa-solid fa-phone"></i></span>
            </div>
        </div>

        <button class="btn-submit" onclick="generateCode()">
            <i class="fa-solid fa-key"></i> پیئرنگ کوڈ حاصل کریں
        </button>

        <div class="result-box" id="resultBox">
            <p style="font-size: 13px; color: var(--text-muted);">آپ کا پیئرنگ کوڈ:</p>
            <div class="code-display" id="pairingCode">MK-FA-99</div>
            <p style="font-size: 12px; color: var(--accent-green);">واٹس ایپ -> Linked Devices -> Link with phone number پر درج کریں</p>
        </div>

        <div class="instructions">
            <h3><i class="fa-solid fa-circle-info" style="color: var(--accent-green);"></i> استعمال کرنے کا طریقہ:</h3>
