# taki11111.github.io
<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org">
<head>
<link th:href="@{/style.css}" rel="styleSheet">
<meta charset="UTF-8">
<title>Mr.Holiday</title>
</head>
<body class="top画面">
<div id="home" class="big-bg">
	<header class="main-nav">
		<h1 class="title">Mr.Holiday</h1>
		<h2 class="subtitle">(休日予定計画が出来るアプリ)</h2>
		<div class="top-btn">
		<a class="item btn btn-flat" th:href="@{/hobit}"><span>趣味・遊び一覧</span></a>
				<a class="item btn btn-flat" th:href="@{/favorite}"><span>お気に入り一覧</span></a></div>
	</header>
	</div><!-- /#home -->
</body>
</html>
