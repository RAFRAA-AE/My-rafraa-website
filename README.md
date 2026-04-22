<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>براندي - الأزياء العصرية</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: #f8f9fa;
        }
        
        .header {
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo h1 {
            color: #333;
            font-size: 28px;
            font-weight: bold;
        }
        
        .search-bar {
            display: flex;
            width: 400px;
            border: 2px solid #ddd;
            border-radius: 25px;
            overflow: hidden;
        }
        
        .search-bar input {
            flex: 1;
            padding: 12px 20px;
            border: none;
            outline: none;
            font-size: 14px;
        }
        
        .search-bar button {
            background: #333;
            border: none;
            color: white;
            padding: 12px 20px;
            cursor: pointer;
        }
        
        .header-icons {
            display: flex;
            gap: 20px;
            align-items: center;
        }
        
        .header-icons a {
            color: #333;
            font-size: 20px;
            text-decoration: none;
            position: relative;
        }
        
        .badge {
            position: absolute;
            top: -8px;
            right: -8px;
            background: #e74c3c;
            color: white;
            border-
