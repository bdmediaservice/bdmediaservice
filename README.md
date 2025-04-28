<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <title>ফাইল ডাউনলোড করার আগে সাবস্ক্রাইব করুন</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 50px;
        }
        button {
            padding: 15px 25px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 8px;
            background-color: #4CAF50;
            color: white;
        }
        button:disabled {
            background-color: grey;
            cursor: not-allowed;
        }
    </style>
</head>
<body>

    <h1>ফাইল ডাউনলোড করতে প্রথমে ভিডিও দেখুন ও লাইক দিন</h1>

    <div id="step1">
        <button onclick="openVideo()">ভিডিও দেখুন</button>
    </div>

    <div id="step2" style="display:none;">
        <button onclick="likeVideo()">লাইক করুন</button>
    </div>

    <div id="step3" style="display:none;">
        <a id="downloadLink" href=https://youtu.be/zLtG-SgZThY?si=GtV9tIfORpazQ2ZC"download>
            <button>ফাইল ডাউনলোড করুন</button>
        </a>
    </div>

    <script>
        function openVideo() {
            window.open("https://youtu.be/zLtG-SgZThY?si=GtV9tIfORpazQ2ZC", "_blank");
            document.getElementById('step1').style.display = 'none';
            document
