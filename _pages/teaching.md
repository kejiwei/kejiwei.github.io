<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>课程名称 - 教师名称</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --text-color: #1f2937;
            --bg-color: #ffffff;
            --hover-color: #3b82f6;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
        }
        
        nav {
            background-color: #f3f4f6;
            padding: 1rem 0;
            margin-bottom: 2rem;
        }
        
        nav ul {
            list-style: none;
            display: flex;
            gap: 2rem;
        }
        
        nav a {
            color: var(--text-color);
            text-decoration: none;
            font-weight: 500;
        }
        
        nav a:hover {
            color: var(--primary-color);
        }
        
        section {
            margin-bottom: 3rem;
            padding: 2rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        
        h1, h2, h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }
        
        .week-content {
            border-left: 4px solid var(--primary-color);
            padding-left: 1rem;
            margin-bottom: 1.5rem;
        }
        
        .calendar {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }
        
        .calendar-item {
            padding: 1rem;
            background-color: #f3f4f6;
            border-radius: 4px;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1rem 0;
        }
        
        th, td {
            padding: 0.75rem;
            text-align: left;
            border-bottom: 1px solid #e5e7eb;
        }
        
        th {
            background-color: #f9fafb;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>课程名称</h1>
            <p>教师名称 | 开课学期 | 课程编号</p>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#intro">课程简介</a></li>
                <li><a href="#weekly">每周内容</a></li>
                <li><a href="#homework">作业要求</a></li>
                <li><a href="#references">参考资料</a></li>
                <li><a href="#evaluation">考核方式</a></li>
                <li><a href="#calendar">教学日历</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section id="intro">
            <h2>课程简介</h2>
            <p>本课程的教学目标、主要内容、预期收获等基本信息</p>
            <ul>
                <li>课程目标：...</li>
                <li>预修要求：...</li>
                <li>教学方式：...</li>
            </ul>
        </section>

        <section id="weekly">
            <h2>每周内容</h2>
            <div class="week-content">
                <h3>第1周：课程导论</h3>
                <ul>
                    <li>课程内容：...</li>
                    <li>重点难点：...</li>
                    <li>课前准备：...</li>
                </ul>
            </div>
            <!-- 更多周内容 -->
        </section>

        <section id="homework">
            <h2>作业要求</h2>
            <table>
                <tr>
                    <th>作业类型</th>
                    <th>截止时间</th>
                    <th>权重</th>
                    <th>要求说明</th>
                </tr>
                <tr>
                    <td>平时作业</td>
                    <td>每周五23:59</td>
                    <td>30%</td>
                    <td>具体要求说明...</td>
                </tr>
                <!-- 更多作业信息 -->
            </table>
        </section>

        <section id="references">
            <h2>参考资料</h2>
            <h3>教材</h3>
            <ul>
                <li>主教材：...</li>
                <li>参考书：...</li>
            </ul>
            <h3>在线资源</h3>
            <ul>
                <li>网站链接：...</li>
                <li>视频资源：...</li>
            </ul>
        </section>

        <section id="evaluation">
            <h2>考核方式</h2>
            <table>
                <tr>
                    <th>评分项目</th>
                    <th>占比</th>
                    <th>说明</th>
                </tr>
                <tr>
                    <td>平时成绩</td>
                    <td>30%</td>
                    <td>包括出勤、作业完成情况等</td>
                </tr>
                <!-- 更多评分项目 -->
            </table>
        </section>

        <section id="calendar">
            <h2>教学日历</h2>
            <div class="calendar">
                <div class="calendar-item">
                    <h3>第1-4周</h3>
                    <ul>
                        <li>理论基础</li>
                        <li>基本概念</li>
                    </ul>
                </div>
                <!-- 更多教学周 -->
            </div>
        </section>
    </main>
</body>
</html>
