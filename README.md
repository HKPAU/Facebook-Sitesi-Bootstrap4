# Facebook-Sitesi-Bootstrap4
<!DOCTYPE html>
<html>
<head>
	<title>Bootsrap 4 Entegre</title>
	<meta charset="utf8">
	<meta name="description" content="Free Web tutorials">
  	<meta name="keywords" content="HTML,CSS,XML,JavaScript">
  	<meta name="author" content="John Doe">
  	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">


	<style type="text/css">
		.ustalan{
			background-color: #405d9b;
			min-height: 80px;
		}

		.text{
			border-radius: 0px !important;
			padding: 0px !important;
			height: 22px;
			border: 0px;
		}

		.posta{
			position: absolute;
			margin-top: -25px;
			color: white;
			font-size: 12px;
			font-style: tahoma;
		}

		.sifre{
			position: absolute;
			color: white;
			font-size: 12px;
			font-style: tahoma;
			margin: -25px 0 0 165px;
		}
		.uyarı{
			position: absolute;
			font-size: 12px;
			font-style: tahoma;
			margin: 25px 0 0 165px;
			
			color: #9CB4D0;

		}

		.ortaalan{
			background: linear-gradient(white,#D4D9E8);
		}

		.dtarih{
			padding: 0px;
			width: 65px;
			height: 35px;
			border-radius:0px;
		}

		.alt{
			margin:20px 0 0 0;
			font:12px tahoma;
		}
		.alt2{
			font:12.75px tahoma;
		}

	</style>
</head>
<body>
	
<nav class="navbar navbar-expand-lg navbar-dark ustalan">
	<div class="container">
		<a href="#"><img src="logo.png"></a>

		<form class="form-inline my-lg-0">
			<label class="posta">E-Posta veya Telefon</label>
			<input type="text" class="form-control form-control-sm mr-2 text" name="">
			<label class="sifre">Şifre</label>
			<input type="text" class="form-control form-control-sm mr-2 text" name="">
			<button type="button" class="btn btn-sm text-white" style="border-color: black;">Giriş Yap</button>
			<label class="uyarı">Hesabını mı Unuttun?</label>
		</form>
	</div>
</nav>


<div class="container-fluid ortaalan">
	<div class="col-md-12">
		<div class="container mt-4">
			<div class="row">
				<div class="col-md-6">
					<h4 style="color: #0E385F;">Facebook tanıdıklarınla iletişim kurmanı ve hayatında olup bitenleri paylaşmanı sağlar</h4>

					<img src="home.png">
				</div>
				<div class="col-md-6">
					<h1>Yeni Bir Hesap Oluştur</h1>
					<h5>Ücretsizdir ve her zaman ücretsiz kalacaktır.</h5>
						
						<form>
							<div class="form-row">
								<div class="form-group col-md-6">
									<input type="email" class="form-control" placeholder="Adın" name="">
								</div>

								<div class="form-group col-md-6">
									<input type="text" class="form-control" placeholder="Soyadın" name="">
								</div>

								<div class="form-group col-md-12">
									<input type="text" class="form-control" placeholder="Cep Telefonu Numaran veya E-Posta" name="">
								</div>


								<div class="form-group col-md-12">
									<input type="text" class="form-control" placeholder="Yeni Şifre" name="">
								</div>
							</div>

							<h3 style="color: grey;">Doğum Tarihi</h3>
							<div class="form-row">	
								<select class="form-control dtarih">
									<option selected>1</option>
									<option>2</option>
									<option>3</option>
									<option>4</option>
								</select>

								<select class="form-control dtarih">
									<option selected>Ocak</option>
									<option>Şubat</option>
									<option>Mart</option>
									<option>Nisan</option>
								</select>

								<select class="form-control dtarih">
									<option selected>1999</option>
									<option>1997</option>
									<option>1996</option>
									<option>1995</option>
								</select>
							</div>

							<i class="fa fa-question-circle ml-2" aria-hidden="true"></i>

							<h3 style="color: grey;" class="mt-3">Cinsiyet</h3>

							<input type="radio" name="">
							<label><strong>Kadın</strong></label>


							<input type="radio" class="ml-4" name="">
							<label><strong>Erkek</strong></label>


							<input type="radio" class="ml-4" name="">
							<label><strong>Özel</strong></label>

							<i class="fa fa-question-circle ml-2" aria-hidden="true"></i>

							<br>

							<button class="btn btn-sm btn-success col-md-12 mt-3" style="font: 22px tahoma; width: 210px ; height: 40px; border-color: green;"><strong>K&nbsp;a&nbsp;y&nbsp;d&nbsp;o&nbsp;l</strong></button>

							<h6 class="col-md-8 mt-2" style="font:12px tahoma; color: grey;">Kaydol düğmesine tıklayarak, <a href="">Koşullarımızı</a>,<a href=""> Veri İlkemizi</a> ve <a href="">Çerezler İlkemizi</a> kabul etmiş olursun. Bizden SMS Bildirimleri alabilir ve bu bildirimleri istediğin zaman durdurabilirsin.</h6>


							<hr>

							<h6 style="color: grey; font-size: 14px;"><strong>Ünlü biri, müzik grubu veya şirket için</strong> <a href="">Sayfa oluştur</a>.</h6>
						</form>

				</div>
			</div>
		</div>
	</div>
</div>

<div class="container">
	<div class="row col-md-12"></div>
		<ul class="nav alt">
			<li class="nav-item ml-2">
				<a href="">Türkçe</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Kurdî (Kurmancî)</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">العربية</a>
			</li>		
			<li class="nav-item ml-2">
				<a href="">English (UK)</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Zaza</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Deutsch</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Русский</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Français (France)</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">فارسی</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Español</a>
			</li>
			<li class="nav-item ml-2">
				<a href="">Português (Brasil)</a>
			</li>
		</ul>

		<hr>	

		<div class="row col-md-12"></div>
		<ul class="nav alt2 col-md-11">
			<li class="nav-item">
				<a href="">Kaydol</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Giriş Yap</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Messenger</a>
			</li>		
			<li class="nav-item ml-3">
				<a href="">Facebook Lite</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Kişiler</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Profiller</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Sayfalar</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Sayfa Kategorileri</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Yerle</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Oyunlar</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Konumlar (Brasil)</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Marketplace</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Gruplar</a>
			</li>
			<li class="nav-item ml-3">
				<a href="">Instagram</a>
			</li>	

			<li class="nav-item mt-2 ml-0">
				<a href="">Yerel</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Bağış Kampanyaları</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Hizmetler</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Reklam Oluştur</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Sayfa Oluştur</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Geliştiriciler</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Kariyer Olanakları</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Gizlilik</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Çerezler</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Ad Choices</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Koşullar</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Hesap Güvenliği</a>
			</li>
			<li class="nav-item mt-2">
				<a href="">Giriş Yardımı</a>
			</li>
			<li class="nav-item mt-2 ml-3">
				<a href="">Yardım</a>
			</li>
		</ul>


		<h6 style="color: grey; font:12px tahoma" class="mt-4">Facebook © 2019</h6>
</div>




<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script>
// Example starter JavaScript for disabling form submissions if there are invalid fields
(function() {
	"use strict";
	window.addEventListener("load", function() {
		var form = document.getElementById("needs-validation");
		form.addEventListener("submit", function(event) {
			if (form.checkValidity() == false) {
				event.preventDefault();
				event.stopPropagation();
			}
			form.classList.add("was-validated");
		}, false);
	}, false);
}());
</script>
</body>
</html>
