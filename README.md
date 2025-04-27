<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spin-off of "Project: Event invite"</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f3e9;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #333;
        }
        
        .invitation {
            width: 600px;
            background: linear-gradient(to bottom, #f0e6d2, #e8d8b5);
            border: 15px solid #da291c;
            border-image: repeating-linear-gradient(45deg, #da291c, #da291c 10px, #f8b400 10px, #f8b400 20px) 15;
            padding: 30px;
            position: relative;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        
        .invitation:before {
            content: "";
            position: absolute;
            top: -15px;
            left: -15px;
            right: -15px;
            bottom: -15px;
            border: 2px solid #f8b400;
            pointer-events: none;
        }
        
        .header {
            margin-bottom: 20px;
            position: relative;
        }
        
        .header:after {
            content: "";
            display: block;
            width: 80%;
            height: 2px;
            background: linear-gradient(to right, transparent, #da291c, transparent);
            margin: 15px auto;
        }
        
        h1 {
            color: #da291c;
            font-size: 32px;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: #5a3921;
            font-size: 24px;
            margin: 15px 0;
            font-weight: normal;
        }
        
        .amharic {
            font-family: 'Nyala', 'Abyssinica SIL', sans-serif;
            font-size: 20px;
            color: #5a3921;
            margin: 10px 0;
        }
        
        .details {
            background-color: rgba(255, 255, 255, 0.7);
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
            border-left: 5px solid #da291c;
        }
        
        .detail-item {
            margin: 15px 0;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .detail-item i {
            color: #da291c;
            margin-right: 10px;
            font-size: 20px;
        }
        
        .guest-list {
            background-color: rgba(218, 41, 28, 0.1);
            padding: 15px;
            margin: 20px 0;
            border-radius: 5px;
            text-align: left;
        }
        
        .guest-list h3 {
            color: #5a3921;
            text-align: center;
            border-bottom: 1px dashed #da291c;
            padding-bottom: 10px;
        }
        
        .guest-list ul {
            columns: 2;
            list-style-type: none;
            padding: 0;
        }
        
        .guest-list li {
            padding: 5px 0;
            position: relative;
            padding-left: 20px;
        }
        
        .guest-list li:before {
            content: "•";
            color: #da291c;
            position: absolute;
            left: 0;
        }
        
        .rsvp-button {
            background-color: #da291c;
            color: white;
            border: none;
            padding: 12px 30px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 30px;
            margin-top: 20px;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 4px 8px rgba(218, 41, 28, 0.3);
        }
        
        .rsvp-button:hover {
            background-color: #b82219;
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(218, 41, 28, 0.4);
        }
        
        .decoration {
            position: absolute;
            width: 60px;
            height: 60px;
            background-color: #f8b400;
            transform: rotate(45deg);
            opacity: 0.2;
        }
        
        .decoration-1 {
            top: 20px;
            left: 20px;
        }
        
        .decoration-2 {
            bottom: 20px;
            right: 20px;
        }
        
        .footer {
            margin-top: 30px;
            font-style: italic;
            color: #5a3921;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="invitation">
        <div class="decoration decoration-1"></div>
        <div class="decoration decoration-2"></div>
        
        <div class="header">
            <h1>Wedding Celebration</h1>
            <div class="amharic">መርዓ መቅደስ</div>
            <h2>Alemu & Selam</h2>
            <div class="amharic">አለሙ እና ሰላም</div>
        </div>
        
        <div class="details">
            <div class="detail-item">
                <i class="fas fa-calendar-alt"></i>
                <span>Saturday, 12th of Meskerem 2016 E.C.<br>September 21, 2024</span>
            </div>
            
            <div class="detail-item">
                <i class="fas fa-clock"></i>
                <span>2:00 PM (8:00 AM Local Time)</span>
            </div>
            
            <div class="detail-item">
                <i class="fas fa-map-marker-alt"></i>
                <span>Addis Ababa Hall<br>123 Bole Road, Addis Ababa</span>
            </div>
        </div>
        
        <div class="guest-list">
            <h3>Honored Guests</h3>
            <ul>
                <li>Ato Kebede and Family</li>
                <li>Wro Almaz and Family</li>
                <li>Dr. Tesfaye</li>
                <li>Ato Girma</li>
                <li>Wro Genet</li>
                <li>Ato Yohannes</li>
                <li>Wro Aster</li>
                <li>Dr. Samuel</li>
                <li>Ato Michael</li>
                <li>Wro Bethlehem</li>
            </ul>
        </div>
        
        <p>Join us as we celebrate our union with traditional music, coffee ceremony, and feast!</p>
        
        <button class="rsvp-button">RSVP by november 30</button>
        
        <div class="footer">
            "Love is the thread that weaves two hearts into one family"
        </div>
    </div>
</body>
</html>
