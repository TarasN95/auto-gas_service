<?php
//Если форма отправлена
if(isset($_POST['submit'])) {

	//Проверка Поля ИМЯ
	if(trim($_POST['contactname']) == '') {
		$hasError = true;
	} else {
		$name = trim($_POST['contactname']);
	}

	//Проверка поля ТЕМА
	if(trim($_POST['subject']) == '') {
		$hasError = true;
	} else {
		$subject = trim($_POST['subject']);
	}

	//Проверка правильности ввода EMAIL
	if(trim($_POST['email']) == '')  {
		$hasError = true;
	} else if (!eregi("^[A-Z0-9._%-]+@[A-Z0-9._%-]+\.[A-Z]{2,4}$", trim($_POST['email']))) {
		$hasError = true;
	} else {
		$email = trim($_POST['email']);
	}

	//Проверка наличия ТЕКСТА сообщения
	if(trim($_POST['message']) == '') {
		$hasError = true;
	} else {
		if(function_exists('stripslashes')) {
			$comments = stripslashes(trim($_POST['message']));
		} else {
			$comments = trim($_POST['message']);
		}
	}

	//Если ошибок нет, отправить email
	if(!isset($hasError)) {
		$emailTo = 'name@yourdomain.com'; //Сюда введите Ваш email
		$body = "Name: $name \n\nEmail: $email \n\nSubject: $subject \n\nComments:\n $comments";
		$headers = 'From: My Site <'.$emailTo.'>' . "\r\n" . 'Reply-To: ' . $email;

		mail($emailTo, $subject, $body, $headers);
		$emailSent = true;
	}
}
?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
        "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ru" lang="ru">
<head>
<title>Автосервіс | Зв'язок</title>
<META HTTP-EQUIV="Content-Type" content="text/html; charset=windows-1251">
<link href="favicon.ico" rel="shortcut icon" type="image/x-icon" />
<link rel="stylesheet" href="css/reset.css" type="text/css" media="screen">
<link rel="stylesheet" href="css/style.css" type="text/css" media="screen">
<link rel="stylesheet" href="css/grid.css" type="text/css" media="screen">
<script src="js/jquery-1.7.1.min.js" type="text/javascript"></script>
<script src="js/cufon-yui.js" type="text/javascript"></script>
<script src="js/cufon-replace.js" type="text/javascript"></script>
<script src="js/Vegur_500.font.js" type="text/javascript"></script>
<script src="js/FF-cash.js" type="text/javascript"></script>
<script src="js/jquery.min.js" type="text/javascript"></script>
<script src="js/jquery.validate.pack.js" type="text/javascript"></script>
<script type="text/javascript">
$(document).ready(function(){
	$("#contact-form").validate();
});
</script>
<!--[if lt IE 9]>
<script type="text/javascript" src="js/html5.js"></script>
<link rel="stylesheet" href="css/ie.css" type="text/css" media="screen">
<![endif]-->
</head>
<body id="page6">
<div class="main-bg">
  <div class="bg">
    <!--==============================header=================================-->
    <header>
      <div class="main">
        <div class="wrapper">
          <h1><a href="index.html">Авто-газ сервіс</a></h1>
          <div class="fright">
            <div class="indent"> <span class="address">79040 Львів, вул. Патона 9</span> <span class="phone">Тел: +8-050-349-58-99</span> </div>
          </div>
        </div>
        <nav>
          <ul class="menu">
            <li><a href="index.html">Головна</a></li>
            <li><a href="about.html">Про нас</a></li>
            <li><a href="maintenance.html">Обслуговування</a></li>
            <li><a href="repair.html">Майстерня</a></li>
            <li><a href="price.html">Ціни</a></li>
            <li><a class="active" href="locations.html">Зв'язок</a></li>
          </ul>
        </nav>
      </div>
    </header>
    <!--==============================content================================-->
    <section id="content">
      <div class="main">
        <div class="container_12">
          <div class="wrapper p5">
            <article class="grid_4">
              <div class="wrapper">
                <figure class="img-indent"><img src="images/page1-img1.png" alt=""></figure>
                <div class="extra-wrap">
                  <h4>Установка ГБО</h4>
                  <p class="p2">Переобладнання автомобілів на газ (пропан-бутан) </p>
                  <a class="button" href="gbo.html">Взнати більше</a> </div>
              </div>
            </article>
            <article class="grid_4">
              <div class="wrapper">
                <figure class="img-indent"><img src="images/page1-img2.png" alt=""></figure>
                <div class="extra-wrap">
                  <h4>Ходова частина</h4>
                  <p class="p2">Стан ходової частини автомобіля визначає його поведінку на дорозі.</p>
                  <a class="button" href="hodova.html">Взнати більше</a> </div>
              </div>
            </article>
            <article class="grid_4">
              <div class="wrapper">
                <figure class="img-indent"><img src="images/page1-img3.png" alt=""></figure>
                <div class="extra-wrap">
                  <h4>Автозапчастини</h4>
                  <p class="p2">Поможемо підібрати і встановити автозапчастини на Ваше авто.</p>
                  <a class="button" href="a-z.html">Взнати більше</a> </div>
              </div>
            </article>
          </div>
          <div class="container-bot">
            <div class="container-top">
              <div class="container">
                <div class="wrapper">
                  <article class="grid_8">
                    <div class="indent-left">
                      <h3 class="p1">Зворотній з'язок</h3>
					  <div class="cont">
                      <?php if(isset($hasError)) { //Если найдены ошибки ?>
		<p class="error">Перевірте будь ласка правильність заповнення полів.</p>
	<?php } ?>

	<?php if(isset($emailSent) && $emailSent == true) { //Если письмо отправленл ?>
		<p><strong>Email вдало відправлено!</strong></p>
		<p>Дякуємо <strong><?php echo $name;?></strong> за використання контактної форми! Ваш email був відправлений і ми зв'яжемось з Вами.</p>
	<?php } ?>

	<form method="post" action="<?php echo $_SERVER['PHP_SELF']; ?>" id="contact-form">
		<div>
		    <label for="name"><span class="text-form">Ім'я:</span></label>
			<input type="text" size="50" name="contactname" id="contactname" value="" class="required" />
		</div>

		<div>
			<label for="email"><span class="text-form">Email:</span></label>
			<input type="text" size="50" name="email" id="email" value="" class="required email" />
		</div>

		<div>
			<label for="subject"><span class="text-form">Тема:</span></label>
			<input type="text" size="50" name="subject" id="subject" value="" class="required" />
		</div>

		<div>
			<label for="message"><span class="text-form">Повідомлення:</span></label>
			<textarea rows="5" cols="50" name="message" id="message" class="required"></textarea>
		</div>
		<div class="butt"><input type="reset" name="reset" value="Очистити" style="width:100px"> <input type="submit" name="submit" value="Відправити" style="width:100px; margin-left:20px;"></div>
	</form>
	</div>
                    </div>
                  </article>
				  
                  <article class="grid_4">
                    <div class="indent-left2 indent-top">
                      <div class="box p4">
                        <div class="padding">
                          <div class="wrapper">
                            <figure class="img-indent"><img src="images/page1-img4.png" alt=""></figure>
                            <div class="extra-wrap">
                              <h3 class="p0">Час роботи:</h3>
                            </div>
                          </div>
                          <p class="color-1 p0">Понеділок-п'ятниця: 8:30-19:00</p>
                          <p class="color-1 p1">Субота: 9:00-16:00</p>
                          <p class="color-1 p1">Неділя - вихідний.</p>
                      </div>
                      <figure class="indent-bot">
                        <iframe width="260" height="202" src="https://maps.google.com.ua/maps?f=q&amp;source=s_q&amp;hl=uk&amp;geocode=&amp;q=%D1%83%D0%BB.+%D0%A8%D0%B0%D1%83%D0%BC%D1%8F%D0%BD%D0%B0,+8,+%D0%A2%D0%B0%D0%B3%D0%B0%D0%BD%D1%80%D0%BE%D0%B3,+%D0%A0%D0%BE%D1%81%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C,+%D0%A0%D0%BE%D1%81%D1%96%D1%8F&amp;aq=&amp;sll=47.265878,38.933895&amp;sspn=0.0064,0.013937&amp;g=%D1%83%D0%BB.+%D0%A8%D0%B0%D1%83%D0%BC%D1%8F%D0%BD%D0%B0,+7,+%D0%A2%D0%B0%D0%B3%D0%B0%D0%BD%D1%80%D0%BE%D0%B3,+%D0%A0%D0%BE%D1%81%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C,+%D0%A0%D0%BE%D1%81%D1%96%D1%8F&amp;ie=UTF8&amp;hq=&amp;hnear=%D1%83%D0%BB.+%D0%A8%D0%B0%D1%83%D0%BC%D1%8F%D0%BD%D0%B0,+8,+%D0%A2%D0%B0%D0%B3%D0%B0%D0%BD%D1%80%D0%BE%D0%B3,+%D0%A0%D0%BE%D1%81%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C,+%D0%A0%D0%BE%D1%81%D1%96%D1%8F,+347909&amp;ll=47.265878,38.933895&amp;spn=0.0032,0.006968&amp;t=m&amp;z=14&amp;output=embed"></iframe><br/>
                      </figure>
                      <div class="indent-left">
                        <dl class="main-address">
                          <dt>79040 Львів, вул. Патона 9<br>
                          <dd><span>Телефон:</span> +8-050-349-58-99;</dd>
                          <dd><span>E-mail:</span><a href="#">avto-gaz-lviv@gmail.com</a></dd>
                        </dl>
                      </div>
                    </div>
                  </article>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--==============================footer=================================-->
      <footer>
      <div class="main"> By <a target="_blank" href="http://vk.com/taras_ivanitsky">Taras Ivanitsky</a> </div>
    </footer>
  </div>
</div>
<script type="text/javascript">Cufon.now();</script>
</body>
</html>