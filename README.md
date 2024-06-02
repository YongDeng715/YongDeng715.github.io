<!DOCTYPE html>

<html lang="en">
<head>
	<meta charset="UTF-8">
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #eef2f5;
		}

		h1, h2, h3 {
			color: #8500aa;
			text-align: center;
			margin-bottom: 0;
		}

		h1 {
			font-size: 3em; none;
			padding-left: 0;
		}

		li {
			margin-bottom: 0.5em;
		}

		a {
			color: #8500aa;
			text-decoration: none;
			font-weight: bold;
			padding: 0.1em 0.3em;
			border-radius: 3px;
			background-color: #f2f2f2;
			transition: background-color 0.2s ease-in-out;
		}

		a:hover {
			background-color: #8500aa;
			color: #fff;
		}
	</style>
</head>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Webpage</title>
    <style>
        body { font-family: Arial, sans-serif; }
        header { text-align: center; margin-top: 20px; }
        nav { margin-top: 20px; text-align: center; }
        nav button { margin: 0 5px; }
        section { display: none; margin: 20px; }
        section.active { display: block; }
    </style>
</head>

<body>  
    <nav>
        <button onclick="showSection('cn')">中文</button>
        <button onclick="showSection('en')">English</button>
        <button onclick="showSection('jp')">日本語</button>
    </nav>
    
    <section id="cn" class="active">
        <header>
            <h1>邓勇的个人网页</h1>
        </header>

        <h2>基本信息</h2>
        <p>姓名：邓勇</p>
        <p>职业：研究生</p>
        <p>所在城市：中国，南京</p>
        <p>简介：我本科毕业于西安交通大学自动化专业，现在就读于中国科学院自动化研究所。</p>
        
        <h2>联系方式</h2>
        <ul>
            <li>Github: <a href="https://github.com/YongDeng715#">github.com/YongDeng715</a></li>
            <li>个人主页：<a href="https://yongdeng715.github.io/#">github.com/yongdeng715.github.io</a></li>
            <li>电子邮件：zhangsan@example.com</li>
            <li><a href="#">其他联系方式</a>
                <p><a href="https://www.zhihu.com/people/deng-xiao-yong-37">知乎(里面有些很有趣的文章哦哦)</a></p>
                <p><a href="https://blog.csdn.net/Cosmosity">我的博客(已经不更新了,现在在知乎写文章)</a></p>
            </li>
        </ul>
        <h2>教育背景</h2>
        <p>西安交通大学 - 自动化学士 (2015-2019)</p>
        <p>中国科学院自动化研究所 - 研究生 (2019-至今)</p>

        <h2>技能</h2>
        <ul>
            <li>编程语言：Python, C++</li>
            <li>机器学习与人工智能</li>
        </ul>

        <h2>项目作品</h2>
        <ul>
			<li><a href="#">项目一</a></li>
			<li><a href="#">项目二</a></li>
			<li><a href="#">项目三</a></li>
            <li>项目1：自动驾驶系统</li>
            <li>项目2：智能机器人</li>
        </ul>
    </section>
    
    <section id="en">
        <header>
            <h1>Deng Yong's Personal Webpage</h1>
        </header>

        <h2>Basic Information</h2>
        <p>Name: Zhang San</p>
        <p>Profession: Graduate Student</p>
        <p>City: Beijing, China</p>
        <p>Introduction: I graduated from Xi'an Jiao Tong University with a major in Automation and am currently studying at the Institute of Automation, Chinese Academy of Sciences.</p>

        <h2>Contact Information</h2>
        <ul>
            <li>Github: <a href="https://yongdeng715.github.io/#">github.com/yongdeng715.github.io</a></li>
            <li>Email: zhangsan@example.com</li>
            <li><a href="#">Connect</a>
                <p><a href="https://www.zhihu.com/people/deng-xiao-yong-37">Zhihu(里面有些很有趣的文章哦哦)</a></p>
                <p><a href="https://blog.csdn.net/Cosmosity">My CSDN Blog(已经不更新了,现在在知乎写文章)</a></p>
            </li>
        </ul>
        <h2>Education</h2>
        <p>Xi'an Jiao Tong University - Bachelor in Automation (2015-2019)</p>
        <p>Institute of Automation, Chinese Academy of Sciences - Graduate Student (2019-present)</p>

        <h2>Skills</h2>
        <ul>
            <li>Programming Languages: Python, C++</li>
            <li>Machine Learning and Artificial Intelligence</li>
        </ul>

        <h2>Projects</h2>
        <ul>
            <li>Project 1: Autonomous Driving System</li>
            <li>Project 2: Intelligent Robot</li>
        </ul>
    </section>
    
    <section id="jp">
        <header>
            <h1>陶陽の個人ウェブページ</h1>
        </header>

        <h2>基本情報</h2>
        <p>名前：張 三</p>
        <p>職業：大学院生</p>
        <p>都市：中国、北京</p>
        <p>紹介：西安交通大学で自動化を専攻し卒業し、現在は中国科学院自動化研究所で学んでいます。</p>

        <h2>連絡先</h2>
        <ul>
            <li>Github: <a href="https://yongdeng715.github.io/#">github.com/yongdeng715.github.io</a></li>
            <li>メール： zhangsan@example.com</li>
            <li><a href="#">Connect</a>
                <p><a href="https://www.zhihu.com/people/deng-xiao-yong-37">Zhihu(里面有些很有趣的文章哦哦)</a></p>
                <p><a href="https://blog.csdn.net/Cosmosity">My CSDN Blog(已经不更新了,现在在知乎写文章)</a></p>
            </li>
        </ul>
        <h2>学歴</h2>
        <p>西安交通大学 - 自動化の学士 (2015-2019)</p>
        <p>中国科学院自動化研究所 - 大学院生 (2019-現在)</p>

        <h2>スキル</h2>
        <ul>
            <li>プログラミング言語：Python, C++</li>
            <li>機械学習と人工知能</li>
        </ul>

        <h2>プロジェクト</h2>
        <ul>
            <li>プロジェクト1：自動運転システム</li>
            <li>プロジェクト2：インテリジェントロボット</li>
        </ul>
    </section>

    <script>
        function showSection(lang) {
            document.querySelectorAll('section').forEach(section => {
                section.classList.remove('active');
            });
            document.getElementById(lang).classList.add('active');
        }
    </script>
</body>
</html>
