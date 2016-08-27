# module-
/***Base Styles***/

*  {
	box-sizing: border-box;
}

body {
	margin: 0;
}

header {
	text-align: center;
	margin-bottom: 30px;
}



.Chicken {
	position: absolute;
	left: 20.3%;
	top: 14.5%;
	background-color: pink;
}

.Beef{
	position: absolute;
	left: 57.4%;
	top: 14.3%;
	background-color: red;
}

.Sushi {
	position: absolute;
	left: 88.50%;
	top: 14.50%;
	background-color: yellow;
}


h2{
	border: 2px solid black;
	padding-left: 2%;
	padding-right: 2%;
	
}

p, .p1, .p2, .p3 {
	background-color: grey;
	border: 2px solid black;
	float: left;
	font-weight: bold;
	height: 30%;
	overflow: hidden;
	padding: 35px 10px 10px 10px;
	text-overflow: hidden;
	width: 30.2%;
}

.p1 {
	margin: 20px 15px 10px 30px;
}

.p2 {
	margin: 20px 10px 10px 15px;
}

.p3 {
	margin: 20px 10px 10px 10px;
}


.row {
	width: 100%;
	clear: both;
}

/**Mobile devices**/

@media (max-width: 767px) {
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
	float: left;
	clear: both;

}

.col-xs-1 {
	width: 8.33%;
}

.col-xs-2 {
	width: 16.66%;
}

.col-xs-3 {
	width: 25%;
}

.col-xs-4 {
	width: 33.33%;
}

.col-xs-5 {
	width: 41.66%;
}

.col-xs-6 {
	width: 50%
}

.col-xs-7 {
	width: 58.33%;
}

.col-xs-8 {
	width: 66.66;
}

.col-xs-9 {
	width: 74.99%;
}

.col-xs-10 {
	width: 83.33%;
}

.col-xs-11 {
	width: 91.66%;
}

.col-xs-12 {
	width: 100%;
}

}

/**Tablets**/

@media (min-width: 768px) and (max-width: 991px) {

.col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
	float: left;
	clear: both;
		
}

.col-sm-1 {
	width: 8.33%;
}

.col-sm-2 {
	width: 16.66%;
}

.col-sm-3 {
	width: 25%;
}

.col-sm-4 {
	width: 33.33%;
}

.col-sm-5 {
	width: 41.66%;
}

.col-sm-6 {
	width: 50%;
}

.col-sm-7 {
	width: 58.33%;
}

.col-sm-8 {
	width: 66.66%;
}

.col-sm-9 {
	width: 74.99%;
}

.col-sm-10 {
	width: 83.33%;
}

.col-sm-11 {
	width: 91.66%;
}

.col-sm-12 {
	width: 100%;
}
}

/**Desktop computers**/

@media (min-width: 992px) and (max-width: 1200px) {
.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
	float: left;
	clear: both;
		
}

.col-md-1 {
	width: 8.33;
}

.col-md-2 {
	width: 16.66%;
}

.col-md-3 {
	width: 25%	
}
.col-md-4 {
	width: 33.33%;
}

.col-md-5 {
	width: 41.66%;
}

.col-md-6 {
	width: 50%;
}

.col-md-7 {
	width: 58.33%;
}
.col-md-8 {
	width: 66.66%;
}
.col-md-9 {
	width: 74.99%;
}
.col-md-10 {
	width: 83.33%;
}
.col-md-11 {
	width: 91.66%;
}
.col-md-12 {
	width: 100%;
}
}
