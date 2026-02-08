# naman-sharma53
this is my 10th repository
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Threads Style UI</title>
    <style>
        :root {
            --bg-color: #ffffff;
            --text-main: #000000;
            --text-muted: #999999;
            --border-color: #f0f0f0;
            --thread-line: #e5e5e5;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            margin: 0;
            display: flex;
            justify-content: center;
            padding-top: 50px;
        }

        .thread-container {
            width: 100%;
            max-width: 570px;
            padding: 0 16px;
        }

        /* Post Structure */
        .post {
            display: flex;
            gap: 12px;
            padding-bottom: 20px;
        }

        /* Left Column: Avatar and Thread Line */
        .left-col {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .avatar {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            background-color: #eee;
            border: 1px solid var(--border-color);
        }

        .thread-line {
            width: 2px;
            flex-grow: 1;
            background-color: var(--thread-line);
            margin-top: 8px;
            border-radius: 1px;
        }

        /* Right Column: Content */
        .right-col {
            flex: 1;
        }

        .post-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 4px;
        }

        .username {
            font-weight: 600;
            font-size: 14px;
            cursor: pointer;
        }

        .time {
            font-size: 14px;
            color: var(--text-muted);
        }

        .content-text {
            font-size: 15px;
            line-height: 1.5;
            margin-bottom: 12px;
            color: var(--text-main);
        }

        /* Video Embed */
        .video-box {
            width: 100%;
            border-radius: 10px;
            border: 1px solid var(--border-color);
            overflow: hidden;
            background-color: #000;
        }

        .video-box iframe {
            width: 100%;
            aspect-ratio: 16 / 9;
            border: none;
            display: block;
        }

        /* Interaction Icons */
        .actions {
            display: flex;
            gap: 20px;
            margin-top: 15px;
            color: var(--text-main);
            font-size: 20px;
        }

        .action-icon {
            cursor: pointer;
            transition: opacity 0.2s;
        }

        .action-icon:hover {
            opacity: 0.6;
        }

        .footer-stats {
            margin-top: 12px;
            font-size: 14px;
            color: var(--text-muted);
        }
    </style>
</head>
<body>

    <div class="thread-container">
        <div class="post">
            <div class="left-col">
                <div class="avatar"></div>
                <div class="thread-line"></div>
            </div>
            
            <div class="right-col">
                <div class="post-header">
                    <span class="username">the_aiml_student</span>
                    <span class="time">2h</span>
                </div>
                
                <div class="content-text">
                    Just finished coding a monostable multivibrator logic. The 555 timer is truly a work of art. ⚡️
                </div>

                <div class="video-box">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ?rel=0" allowfullscreen></iframe>
                </div>

                <div class="actions">
                    <span class="action-icon">♡</span>
                    <span class="action-icon">💬</span>
                    <span class="action-icon">⇄</span>
                    <span class="action-icon">✈</span>
                </div>

                <div class="footer-stats">
                    42 replies · 156 likes
                </div>
            </div>
        </div>
    </div>

</body>
</html>
