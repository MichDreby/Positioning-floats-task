# Positioning-floats-task

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
    <title>Document</title>
</head>
<body>
    <div id="root" class="wrapper">
        <section class="rs-calendar">
            <nav class="clndr-nav relative clear-fix">
                <div class="nav-ctn fl-left">
                    <ul>
                        <li class="nav-btn text-center"><a href="#">today</a></li>
                        <li class="nav-btn text-center"><a href="#">prev</a></li>
                        <li class="nav-btn text-center"><a href="#">next</a></li>
                    </ul>
                </div>
                <div class="nav-ctn abs-center">
                    <p class="selectedDate">Date</p>
                </div>
                <div class="nav-ctn fl-right">
                    <ul>
                        <li class="nav-btn text-center"><a href="#">Month</a></li>
                        <li class="nav-btn text-center"><a href="#">Week</a></li>
                    </ul>
                </div>
            </nav>
            <div class="clndr-area">
                <div class="clndr-header">
                    <div class="clndr-row clear-fix">
                        <div class="clndr-cell hdr-col fl-left"><p>Sun</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Mon</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Tue</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Wed</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Thu</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Fri</p></div>
                        <div class="clndr-cell hdr-col fl-left"><p>Sat</p></div>
                    </div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left relative">
                        <p class="cell-date-numb absolute">30</p>
                        <div class="cell-evt hght-3 first-evt">
                            <h4 class="cell-evt-hdr">Webinar</h4>
                            <p class="cell-evt-time">19.30</p>
                        </div>
                        <div class="cell-evt hght-3 second-evt">
                            <h4 class="cell-evt-hdr">Workshop</h4>
                            <p class="cell-evt-time">12.30</p>
                        </div>
                        <div class="cell-evt hght-3 third-evt">
                            <h4 class="cell-evt-hdr">Deadline</h4>
                            <p class="cell-evt-time">12.30</p>
                        </div>
                    </div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
                <div class="clndr-row clear-fix">
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                    <div class="clndr-cell fl-left">1</div>
                </div>
            </div>
        </section>
    </div>

</body>
</html>

****************************************************************
****************************************************************
****************************************************************

* {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
body{
    font-family: Verdana, Arial, sans-serif;
    font-size: 16px;
    /*background-color: #f1f5fb;*/
    color: #fff;
    line-height: 1;
}
a {
    text-decoration: none;
    color: inherit;
}
h1, h2, h3, h4, h5 {
    font-weight: normal;
}
/**********************************/
.wrapper {
    margin: 20px auto;
    width: 890px;

}
/**********************************/
.clndr-nav{
    margin-bottom: 20px;
}
.nav-ctn .nav-btn{
    list-style-type: none;
    display: inline-block;
    min-width: 40px;
    height: 30px;
    user-select: none;
    border: 1px solid;
    background-color: #ccc;
    border-radius: 3px;
    border-color: #aaa;
}
.nav-ctn .nav-btn:hover{
    cursor: pointer;
    background-color: #ddd;
}
.nav-ctn .nav-btn>a{
    padding: 0 5px;
    line-height: 30px;
}
.nav-ctn .active-nav-type{
    background-color: #aaa;
}
/**********************************/
.clndr-header{
    /*margin-bottom: 50px;*/
}
.hdr-col{
    height: 30px;
}
/**********************************/
.clndr-area{
    /*border: 1px solid #aaa;*/
}




.clndr-cell{
    width: -webkit-calc(100%/7);
    width: -moz-calc(100%/7);
    width: -o-calc(100%/7);
    background-color: #5d5d5d;
    font-family: 'Open Sans', sans-serif;
}
.clndr-cell .cell-date-numb {
    font-size: 20px;
    font-weight: 500;
    top: 3px;
    left: 3px;
}
.clndr-cell .cell-evt {
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 45px;
    border-bottom: 1px solid #fff;
}
.cell-evt.hght-1 {
    height: -webkit-calc(100%/1);
    height: -moz-calc(100%/1);
    height: -o-calc(100%/1);
}
.cell-evt.hght-2 {
    height: -webkit-calc(100%/2);
    height: -moz-calc(100%/2);
    height: -o-calc(100%/2);
}
.cell-evt.hght-3 {
    height: -webkit-calc(100%/3);
    height: -moz-calc(100%/3);
    height: -o-calc(100%/3);
}
.clndr-cell .cell-evt.first-evt{
    background-color: #64bd6b;
}
.clndr-cell .cell-evt.second-evt{
    background-color: #54c3bc;
}
.clndr-cell .cell-evt.third-evt{
    background-color: #2a579b;
}

.clndr-cell .cell-evt:last-child{
    border-bottom: none;
}
.clndr-cell .cell-evt-hdr {
    font-size: 14px;
    margin-bottom: 3px;
}
.clndr-cell .cell-evt-time {
    font-size: 12px;
}



.clndr-cell:not(.hdr-col){
    border-top: 12.5px solid #fff;
    border-bottom: 12.5px solid #fff;
    border-left: 3px solid #fff;
    border-right: 3px solid #fff;

}
.clndr-cell.current-day{
    border: 5px solid #aaa;
    background-color: #dadada;
    font-weight: 600;
}
.clndr-cell:not(.hdr-col){
    height: 150px;
}
.clndr-cell.week-nav-type {
    height: 500px;
}
.clndr-cell.another-month {
    color: #aaa;
}
.clndr-cell:not(.hdr-col):hover{
    /*background-color: #dad8d8;*/
}
/**********************************/
.text-center {
    text-align: center;
}
.abs-center{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.relative{
    position: relative;
}
.absolute{
    position: absolute;
}
.fl-left{
    float: left;
}
.fl-right{
    float: right;
}
.clear-fix::after{
	content: '';
	display: block;
	clear: both;
	height: 0;
	visibility: hidden;
}


