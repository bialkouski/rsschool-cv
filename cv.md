# YAUHENI BIALKOUSKI
**+375(29)654-38-44
yauheni.bialkouski@gmail.com**

#### I want to start my career as a JavaScript developer at EPAM and become a team lead in 5 years!
#### I have good analytical skills. I can easily do self-study.
#### I have good teamwork skills.

#### I have basic experience with HTML / CSS, JavaScript, PHP, Mysql, Git.

## Code examples
`<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<div id="menu">
		<button data-action='load'>Загрузить</button>
		<button data-action='save'>Сохранить</button>
		<button data-action='search'>Поиск</button>
	</div>
	<script type="text/javascript">		
		function Menu(elem){
			  this.load = function(){
				alert("Загружаю.....!");
			};
			this.save =function(){
				alert("Сохраняю...!");
			};
			this.search = function(){
				alert("Ищу...!");
			};
			let self = this;
			elem.onclick = function(e){
				let target = e.target;
				let action = target.getAttribute('data-action');
				if(action){
					self[action]();
				}
			};
		};
		new Menu(menu);
	</script>
</body>
</html>`

### Education
  Bauman Moscow State Technical University (BMSTU).
  Also Ш ещщл online PHP courses.
  

#### A2 English level
