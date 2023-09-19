<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">

    <title>Shop</title>
    <link href="css/bootstrap.min.css" rel="stylesheet">
	<link href="css/style.css" rel="stylesheet">
	<!-- jQuery -->
    <script src="js/jquery.js"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="js/bootstrap.min.js"></script>
	
	<script src="js/shop.js"></script>
</head>

<body>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">Shop</a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="html/about.html">About</a>
                    </li>
                    <li>
                        <a href="html/services.html">Services</a>
                    </li>
                    <li>
                        <a href="html/contacts.html">Contact</a>
                    </li>
					
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
        <div class="row">

            <div class="col-md-3">
                <p class="lead">*Shop Name*</p>
				<br>
				<h3><a href="" class="cart-link" data-toggle="modal" data-target="#Cart"> Cart </a> </h3>
            </div>
            <div class="col-md-9">
                <div class="row carousel-holder">

                    <div class="col-md-12">
                        <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
                            <ol class="carousel-indicators">
                                <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
                                <li data-target="#carousel-example-generic" data-slide-to="1"></li>
                                <li data-target="#carousel-example-generic" data-slide-to="2"></li>
                            </ol>
                            <div class="carousel-inner">
                                <div class="item active">
                                    <img class="slide-image" src="img/800x300(1).jpg" alt="">
                                </div>
                                <div class="item">
                                    <img class="slide-image" src="img/800x300(2).jpg" alt="">
                                </div>
                                <div class="item">
                                    <img class="slide-image" src="img/800x300(3).jpg" alt="">
                                </div>
                            </div>
                            <a class="left carousel-control" href="#carousel-example-generic" data-slide="prev">
                                <span class="glyphicon glyphicon-chevron-left"></span>
                            </a>
                            <a class="right carousel-control" href="#carousel-example-generic" data-slide="next">
                                <span class="glyphicon glyphicon-chevron-right"></span>
                            </a>
                        </div>
                    </div>

                </div>

                <div class="row">

                    <div class="col-sm-4 col-lg-4 col-md-4">
                        <div class="thumbnail">
                            <img src="img/goods/320x150(1).jpg" alt="">
                            <div class="caption">
                                <h4 class="pull-right">$24.99</h4>
                                <h4><a href="" data-toggle="modal" data-target="#FirstGoodModal">First Product</a>
                                </h4>
                            </div>
                            <div class="ratings">
                                <p class="pull-right">15 reviews</p>
                                <p>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-sm-4 col-lg-4 col-md-4">
                        <div class="thumbnail">
                            <img src="img/goods/320x150(2).jpg" alt="">
                            <div class="caption">
                                <h4 class="pull-right">$64.99</h4>
                                <h4><a href="" data-toggle="modal" data-target="#SecondGoodModal">Second Product</a>
                                </h4>
                                <p>This is a short description.</p>
                            </div>
                            <div class="ratings">
                                <p class="pull-right">12 reviews</p>
                                <p>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star-empty"></span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-sm-4 col-lg-4 col-md-4">
                        <div class="thumbnail">
                            <img src="img/goods/320x150(3).jpg" alt="">
                            <div class="caption">
                                <h4 class="pull-right">$74.99</h4>
                                <h4><a href="" data-toggle="modal" data-target="#ThirdGoodModal">Third Product</a>
                                </h4>
                                <p>This is a short description.</p>
                            </div>
                            <div class="ratings">
                                <p class="pull-right">31 reviews</p>
                                <p>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star-empty"></span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-sm-4 col-lg-4 col-md-4">
                        <div class="thumbnail">
                            <img src="img/goods/320x150(4).jpg" alt="">
                            <div class="caption">
                                <h4 class="pull-right">$84.99</h4>
                                <h4><a href="" data-toggle="modal" data-target="#FourthGoodModal">Fourth Product</a>
                                </h4>
                                <p>This is a short description.</p>
                            </div>
                            <div class="ratings">
                                <p class="pull-right">6 reviews</p>
                                <p>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star-empty"></span>
                                    <span class="glyphicon glyphicon-star-empty"></span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-sm-4 col-lg-4 col-md-4">
                        <div class="thumbnail">
                            <img src="img/goods/320x150(5).jpg" alt="">
                            <div class="caption">
                                <h4 class="pull-right">$94.99</h4>
                                <h4><a href="" data-toggle="modal" data-target="#FifthGoodModal">Fifth Product</a>
                                </h4>
                                <p>This is a short description.</p>
                            </div>
                            <div class="ratings">
                                <p class="pull-right">18 reviews</p>
                                <p>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star"></span>
                                    <span class="glyphicon glyphicon-star-empty"></span>
                                </p>
                            </div>
                        </div>
                    </div>

                </div>

            </div>

        </div>

    </div>
    <!-- /.container -->

    <div class="container">

        <hr>

        <!-- Footer -->
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p></p>
                </div>
            </div>
        </footer>

    </div>
    <!-- /.container -->
	
	<div class="modal fade" id="FirstGoodModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Product1</h4>
      </div>
      <div class="modal-body">
	  <img src="img/goods/320x150(1).jpg"
        <p>*description* &hellip;</p>
		<button class="btn-primary add-to-busket-btn"><span class="glyphicon glyphicon-shopping-cart"></span> add to cart </button>
		<div class="add-to-busket-block">
			<button class="btn-primary btn-minus">-</button>
			<input class="form-control count-input" />
			<button class="btn-primary btn-plus">+</button>
			<button class="btn-success"><span class="glyphicon glyphicon-ok ok-1"></span></button>
		</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

<div class="modal fade" id="SecondGoodModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Product2</h4>
      </div>
      <div class="modal-body">
	  <img src="img/goods/320x150(2).jpg"
        <p>*description* &hellip;</p> 
		<button class="btn-primary add-to-busket-btn"><span class="glyphicon glyphicon-shopping-cart"></span> add to cart </button>
		<div class="add-to-busket-block">
			<button class="btn-primary btn-minus">-</button>
			<input class="form-control count-input" />
			<button class="btn-primary btn-plus">+</button>
			<button class="btn-success"><span class="glyphicon glyphicon-ok ok-2"></span></button>
		</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

	<div class="modal fade" id="ThirdGoodModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Product3</h4>
      </div>
      <div class="modal-body">
	  <img src="img/goods/320x150(3).jpg"
        <p>*description* &hellip;</p>
		<button class="btn-primary add-to-busket-btn"><span class="glyphicon glyphicon-shopping-cart"></span> add to cart </button>
		<div class="add-to-busket-block">
			<button class="btn-primary btn-minus">-</button>
			<input class="form-control count-input" />
			<button class="btn-primary btn-plus">+</button>
			<button class="btn-success"><span class="glyphicon glyphicon-ok ok-3"></span></button>
		</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

<div class="modal fade" id="FourthGoodModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Product4</h4>
      </div>
      <div class="modal-body">
	  <img src="img/goods/320x150(4).jpg"
        <p>*description* &hellip;</p>
		<button class="btn-primary add-to-busket-btn"><span class="glyphicon glyphicon-shopping-cart"></span> add to cart </button>
		<div class="add-to-busket-block">
			<button class="btn-primary btn-minus">-</button>
			<input class="form-control count-input" />
			<button class="btn-primary btn-plus">+</button>
			<button class="btn-success"><span class="glyphicon glyphicon-ok ok-4"></span></button>
		</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

<div class="modal fade" id="FifthGoodModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Product5</h4>
      </div>
      <div class="modal-body">
	  <img src="img/goods/320x150(5).jpg"
        <p>*description* &hellip;</p>
		<button class="btn-primary add-to-busket-btn"><span class="glyphicon glyphicon-shopping-cart"></span> add to cart </button>
		<div class="add-to-busket-block">
			<button class="btn-primary btn-minus">-</button>
			<input class="form-control count-input" />
			<button class="btn-primary btn-plus">+</button>
			<button class="btn-success"><span class="glyphicon glyphicon-ok ok-5"></span></button>
		</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

	<div class="modal fade" id="Cart">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Cart</h4>
      </div>
      <div class="modal-body cart-body">
	
      </div>
      <div class="modal-footer">
	  		<button type="button" class="btn btn-default btn-close" OnClick="clearCart(); $('.cart-body').html('');"> Clear cart </button>
        <button type="button" class="btn btn-default btn-close" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary btn-order">Order</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->

</body>

</html>




Файл  style.css

body {
    padding-top: 70px; /* Required padding for .navbar-fixed-top. Remove if using .navbar-static-top. Change if height of navigation changes. */
}

.count-input {
	width:10%;
	display: inline;
}

.add-to-basket-block {
	margin-top: 7px;
}

.modal-image {
	width: 100%;
}

.slide-image {
    width: 100%;
}

.carousel-holder {
    margin-bottom: 30px;
}

.carousel-control,
.item {
    border-radius: 4px;
}

.caption {
    height: 130px;
    overflow: hidden;
}

.caption h4 {
    white-space: nowrap;
}

.thumbnail img {
    width: 100%;
}

.ratings {
    padding-right: 10px;
    padding-left: 10px;
    color: #d17581;
}

.thumbnail {
    padding: 0;
}

.thumbnail .caption-full {
    padding: 9px;
    color: #333;
}
.amount{
    display: inline;
}
.product{
    display: inline;
}
.remove-from-cart{
    display: inline;
}
footer {
    margin: 50px 0;
}



shop.js
$(document).ready(function() {
	
	$('.add-to-busket-block').hide();
		
	$('.add-to-busket-btn').on('click', function() {
		$('.add-to-busket-block').show();
		$('.count-input').val("0");
	});
	
	$('.btn-plus').on('click', function() {
	var a; 
	a= parseInt(($('.count-input').val()))+1;
		$('.count-input').val(a);
	});

	$('.btn-minus').on('click', function() {
	var a; 
	a= parseInt(($('.count-input').val()))-1;
	
		if(a>=0){
		$('.count-input').val(a);
		}
		else{
			a=0;
		}
	});
	
	$('.btn-close').on('click', function() {
	$('.add-to-busket-block').hide();
	});
	
	$('.close').on('click', function() {
	$('.add-to-busket-block').hide();
	});
	
	let cart = new Array();
	cart=[];
	
	$('.ok-1').on('click', function() {
		var a = $('.count-input').val();
		AddToCard(0, a);
	});
	$('.ok-2').on('click', function() {
		var a = $('.count-input').val();
		AddToCard(1, a);
	});
		$('.ok-3').on('click', function() {
		var a = $('.count-input').val();
		AddToCard(2, a);
	});
	$('.ok-4').on('click', function() {
		var a = $('.count-input').val();
		AddToCard(3, a);
	});
		$('.ok-5').on('click', function() {
		var a = $('.count-input').val();
		AddToCard(4, a);
	});
		
	function AddToCard(n, amount){
		if(amount>0) 
		{
			cart[n]=amount; 
		}
	}

	function addRow() {
		for(let i=0; i<cart.length; i++){
		
		if(cart[i]>0){
		/*	document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product"></input>
			<input readonly class="amount"></input>
			</div>`      
			) */
	
			switch(i) {
				case 0:
					//var t = "Product1";
					document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product0"></input>
			<input readonly class="amount0"></input>
			</div>`)
			$('.product0').val("Product1");
			$('.amount0').val(cart[i]);
					break;

				case 1: 
					//var t = "Product2";
					document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product1"></input>
			<input readonly class="amount1"></input>
			</div>`)
			$('.product1').val("Product2");
			$('.amount1').val(cart[i]);
					break;
		
				case 2:
					//var t = "Product3";
					document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product2"></input>
			<input readonly class="amount2"></input>
			</div>`)
			$('.product2').val("Product3");
			$('.amount2').val(cart[i]);
					break;
			
				case 3:
					//var t = "Product4";
					document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product3"></input>
			<input readonly class="amount3"></input>
			</div>`)
			$('.product3').val("Product4");
			$('.amount3').val(cart[i]);
					break;
			
				case 4:
					//var t = "Product5";
					document.querySelector('.cart-body').insertAdjacentHTML(
			'afterbegin',
			`<div class="row">
			<input readonly class="product4"></input>
			<input readonly class="amount4"></input>
			</div>`)
			$('.product4').val("Product5");
			$('.amount4').val(cart[i]);
					break;

				default:
		
				break;
			}
		//$('.product').val(t);
		//$('.amount').val(cart[i]);
		}
		}
	}
	
	window.clearCart = function clearCart(){
		for(let i=0; i<cart.length; i++){
			cart[i]=0;
		}
	}
	$('.cart-link').on('click', function(){
		console.log(cart);
		$('.cart-body').html('');
		addRow();
	});			
});



Файл about.html

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">

    <title>Shop</title>
    <link href="../css/bootstrap.min.css" rel="stylesheet">
	<link href="../css/style.css" rel="stylesheet">

</head>

<body>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <a class="navbar-brand" href="../index.html">Shop</a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
					<li>
                        <a href="#">About</a>
                    </li>
                    <li>
                        <a href="services.html">Services</a>
                    </li>
                    <li>
                        <a href="contacts.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
		        <div class="row">

            <div class="col-md-3">
                <p class="lead">Shop Name</p>
            </div>

            <div class="col-md-9">        

                <div class="row">

                    <p>*Shop description*</p>

                </div>

            </div>

        </div>
	</div>

    <div class="container">

        <hr>

        <!-- Footer -->
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p></p>
                </div>
            </div>
        </footer>

    </div>
    <!-- /.container -->

</body>

</html>



Файл contacts.html

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">

    <title>Shop</title>
    <link href="../css/bootstrap.min.css" rel="stylesheet">
	<link href="../css/style.css" rel="stylesheet">

</head>

<body>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <a class="navbar-brand" href="../index.html">Shop</a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
					<li>
                        <a href="about.html">About</a>
                    </li>
                    <li>
                        <a href="services.html">Services</a>
                    </li>
                    <li>
                        <a href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
		        <div class="row">
            <div class="col-md-3">
                <p class="lead">Shop Name</p>
            </div>
            <div class="col-md-9">        
                <div class="row">
                    <p>Yudin Lex</p>
                </div>
            </div>
        </div>
	</div>

    <div class="container">
        <hr>
        <!-- Footer -->
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p></p>
                </div>
            </div>
        </footer>
    </div>
    <!-- /.container -->
</body>
</html>



Файл services.html

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">

    <title>Shop</title>
    <link href="../css/bootstrap.min.css" rel="stylesheet">
	<link href="../css/style.css" rel="stylesheet">

</head>
<body>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <a class="navbar-brand" href="../index.html">Shop</a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
					<li>
                        <a href="about.html">About</a>
                    </li>
                    <li>
                        <a href="#">Services</a>
                    </li>
                    <li>
                        <a href="contacts.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
		        <div class="row">

            <div class="col-md-3">
                <p class="lead">Shop Name</p>
            </div>
            <div class="col-md-9">        
                <div class="row">
                    <p>*Services*</p>
                </div>
            </div>
        </div>
	</div>

    <div class="container">

        <hr>
        <!-- Footer -->
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p></p>
                </div>
            </div>
        </footer>
    </div>
    <!-- /.container -->

</body>
</html>
