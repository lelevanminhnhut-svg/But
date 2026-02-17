<!DOCTYPE html><html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Cá Nhân</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #74ebd5, #9face6);
            color: #333;
        }.container {
        max-width: 900px;
        margin: 40px auto;
        background: #fff;
        border-radius: 15px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        overflow: hidden;
    }

    .header {
        background: linear-gradient(135deg, #667eea, #764ba2);
        color: white;
        text-align: center;
        padding: 40px 20px;
    }

    .header img {
        width: 130px;
        height: 130px;
        border-radius: 50%;
        border: 4px solid #fff;
        object-fit: cover;
        margin-bottom: 15px;
    }

    .header h1 {
        margin: 10px 0 5px;
    }

    .header p {
        margin: 0;
        font-size: 16px;
        opacity: 0.9;
    }

    .content {
        padding: 30px;
    }

    .section {
        margin-bottom: 30px;
    }

    .section h2 {
        border-left: 5px solid #667eea;
        padding-left: 10px;
        color: #667eea;
        margin-bottom: 15px;
    }

    .info-list {
        list-style: none;
        padding: 0;
    }

    .info-list li {
        margin-bottom: 8px;
    }

    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }

    .skill {
        background: #667eea;
        color: white;
        padding: 6px 12px;
        border-radius: 20px;
        font-size: 14px;
    }

    .projects {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 15px;
    }

    .project {
        border: 1px solid #ddd;
        border-radius: 10px;
        padding: 15px;
        transition: 0.3s;
    }

    .project:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    }

    .footer {
        text-align: center;
        padding: 15px;
        background: #f5f5f5;
        font-size: 14px;
    }
