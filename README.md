<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<body>

    <img src="https://kkimgs.yisou.com/ims?kt=url&at=ori&key=aHR0cHM6Ly93eDEuc2luYWltZy5jbi9tdzIwMDAvZjAzNDQ4MzRseTFpY250YWNsZjUwajIxa3cxa3dxYjMuanBn&sign=yx:v5XXeOX3IUt_4KGEgBgS8ByiSgs=&tv=0_0" alt="梁秋实照片" width="150" height="150">

    <h2>梁秋实</h2>

    <p><font face="楷体" size="3">计算机科学与技术</font></p>

    <h2>我的爱好</h2>

    <h3>热衷(有序)</h3>

    <div style="user-select: none; -webkit-user-select: none;">

    <ol>

    <li>算法与数据结构 <progress value="85" max="100">85%</progress> 85%</li>

        <li>独立游戏开发<progress value="90" max="100">90%</progress>90%</li>

        <li>自然语言处理 <progress value="65" max="100">65%</progress> 65%</li>

        <li>摄影与构图 <progress value="80" max="100">80%</progress> 80%</li>

    </ol>

</div>

   

    <h2>论文·下载</h2>

     <p><font color="gray">输入密码 123456 查看</font></p>



    <input type="password" id="pwd" placeholder="请输入密码">

    <button onclick="showPaper()">解锁</button>

    <button onclick="hidePaper()">隐藏</button>



    <div id="paper" hidden>

        <h3>基于深度学习的时序预测优化</h3>

        <a href="https://example.com/paper.pdf" target="_blank">下载 PDF</a>

    </div>



    <p id="msg"></p>



    <script>

    函数 showPaper() {

            var pwd = document.getElementById("pwd").value;

    如果 (pwd === "123456") {

                document.getElementById("paper").hidden = false;

                document.getElementById("msg").innerHTML = "✅ 解锁成功！";

                document.getElementById("msg").style.color = "green";

            } else {

                document.getElementById("msg").innerHTML = "❌ 密码错误";

                document.getElementById("msg").style.color = "red";

            }

        }



        function hidePaper() {

            document.getElementById("paper").hidden = true;

            document.getElementById("msg").innerHTML = "🔒 已隐藏";

            document.getElementById("msg").style.color = "orange";

        }

    </script>

</body>

</html>

