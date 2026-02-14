<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>For My Pyaari Avni ❤️</title>
    <style>
        :root { --primary-pink: #ff4d6d; --glass: rgba(255, 255, 255, 0.4); }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Georgia', serif; }
        body { background: linear-gradient(135deg, #fff5f7 0%, #f8bbd0 100%); height: 100vh; display: flex; justify-content: center; align-items: center; overflow: hidden; }
        .page { display: none; width: 90%; max-width: 380px; background: var(--glass); backdrop-filter: blur(15px); border-radius: 30px; padding: 25px; text-align: center; box-shadow: 0 8px 32px rgba(0,0,0,0.1); position: relative; max-height: 90vh; overflow-y: auto; }
        .active { display: block; animation: fadeIn 0.5s ease-out; }
        @keyframes fadeIn { from { opacity: 0; transform: scale(0.9); } to { opacity: 1; transform: scale(1); } }
        h1 { color: #d81b60; font-size: 1.4rem; margin-bottom: 15px; }
        .slider-container { width: 100%; aspect-ratio: 1/1; border-radius: 20px; overflow: hidden; margin-bottom: 20px; }
        .slider { display: flex; transition: transform 0.5s ease-in-out; height: 100%; }
        .slide { min-width: 100%; height: 100%; }
        .slide img { width: 100%; height: 100%; object-fit: cover; }
        .btn-group { display: flex; justify-content: center; gap: 20px; margin-top: 10px; }
        .btn-yes { background: var(--primary-pink); color: white; padding: 12px 30px; border-radius: 50px; border: none; font-weight: bold; cursor: pointer; }
        #noBtn { background: #9e9e9e; color: white; padding: 12px 30px; border-radius: 50px; border: none; font-weight: bold; transition: all 0.2s ease; }
        .next-arrow { position: absolute; bottom: 15px; right: 20px; font-size: 2rem; cursor: pointer; }
        .shayri-container { font-style: italic; color: #4a4a4a; line-height: 1.6; font-size: 1rem; }
        .shayri-btn { margin-top: 20px; background: none; border: 2px solid var(--primary-pink); color: var(--primary-pink); padding: 10px 20px; border-radius: 20px; cursor: pointer; }
        #ring { font-size: 100px; display: none; margin: 20px 0; }
        #ring.show { display: block; animation: ringPop 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275); }
        @keyframes ringPop { from { transform: scale(0); } to { transform: scale(1.2); } }
    </style>
</head>
<body>

    <div class="page active" id="page1">
        <h1>AVNI, WILL YOU BE MY VALENTINE? ❤️</h1>
        <div class="slider-container">
            <div class="slider" id="slider">
                <div class="slide"><img src="36923.jpg"></div>
                <div class="slide"><img src="36927.jpg"></div>
                <div class="slide"><img src="36922.jpg"></div>
                <div class="slide"><img src="36924.jpg"></div>
            </div>
        </div>
        <div class="btn-group">
            <button class="btn-yes" onclick="showPage(2)">YES!</button>
            <button id="noBtn">No</button>
        </div>
    </div>

    <div class="page" id="page2">
        <h1 style="font-size: 1.8rem;">I LOVE YOUUUU AVNI 💘</h1>
        <p>Meri pyaari Avni, tum meri duniya ho!</p>
        <div class="next-arrow" onclick="showPage(3)">➡️</div>
    </div>

    <div class="page" id="page3">
        <h1>One more thing...<br>Will you Marry me? 💍</h1>
        <div id="ring">💎💍</div>
        <button class="btn-yes" id="marryBtn" onclick="revealRing()">YES!</button>
        <div id="arzSection" style="display:none; margin-top: 20px;">
            <button class="shayri-btn" onclick="showPage(4)">Arz kiya hai....</button>
        </div>
    </div>

    <div class="page" id="page4">
        <h1 style="color: #d81b60;">AVNI MERI JAAN-E-MAN</h1>
        <div class="shayri-container">
            <p>Kabhi yun bhi aa meri aankhon mein,<br>Jo dhadkan se dhadkan tak jaaye,<br>Woh ek hi naam Avni ho jaaye.</p>
            <p>Main tumhe apni rooh mein basaata hoon.<br>Tum meri aadat nahi, meri ibaadat ho.</p>
            <p>A
            
