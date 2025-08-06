<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>আমার To-Do লিস্ট মিনি অ্যাপ</title>

    <!-- টেলিগ্রাম মিনি অ্যাপ SDK (যদি টেলিগ্রামের ভেতর থেকে এটি ব্যবহার করতে চান) -->
    <!-- ব্রাউজারে এটি খুললে window.Telegram.WebApp অবজেক্টটি undefined থাকবে এবং টেলিগ্রামের ফাংশন কাজ করবে না। -->
    <!-- <script src="https://telegram.org/js/telegram-web-app.js"></script> -->

    <style>
        /* CSS স্টাইল */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5; /* হালকা ধূসর ব্যাকগ্রাউন্ড */
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: flex-start; /* উপরের দিকে শুরু হবে */
            min-height: 100vh;
            box-sizing: border-box;
        }

        .container {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 100%;
            max-width: 500px;
            box-sizing: border-box;
        }

        h1 {
            color: #007bff;
            margin-bottom: 25px;
            font-size: 1.8em;
            font-weight: 6
