# weatherforecast1
<!DOCTYPE html>

<html><head>
        <title>WFC</title>
        <style>
            .weather{
                color:rgb(245, 30, 30);
                font-family: georgia;
                font-size: 30px;
                font-weight: bold;
                display:inline;
            }
            .search-bar{
                font-size: 15px;
                display:inline;
                margin-left: 10px;
                vertical-align:bottom;
                max-width: max-content;
            }
            .search-button{
                color:white;
                border:none;
                height:25px;
                width:60px;
                border-style:solid;
                background-color: red ;
                margin-left: 4px;
                padding: center;
                cursor:pointer;
                vertical-align: bottom;
                display: inline;
                transition:opacity 0.15;
            }
            .search-button:hover{
                opacity: 0.8;
            }
            .details{
                width:200px;
                line-height:5px;
                inline-size:100px;
              }
              .row {
                background-color:#f4ccc0;
                display: inline-block;
            }
            .column {
                float: left;
                padding: 5px;
            }
            table {
                border:1px black;
                border-spacing:2px;
                width:10px;
                  }
            th, td {
                text-align: center;
                padding: 17px;
                margin-top: 4px;
                border: 1px solid black;
                cursor:pointer;
                 }
            tr:nth-child(1) {
                background-color:rgb(124, 119, 119);
                width: 200px;
                padding:center;  
                border: 1px solid black;
                cursor:pointer;
                margin-right: 8px;
                text-align: center;
                transition:opacity 0.15;
            }
            tr:nth-child(1):hover{
            opacity: 0.8;
            }
             tr:nth-child(2) {
                background-color: rgb(124, 119, 119);     
            }
            tr:nth-child(4) {
                background-color: #f2f2f2;
            }
       </style>
       </head>
       <body>
        <div class="wf">
        <p class="weather">Weather forecast
            <input class="search-bar" type="text" placeholder="Enter City">
            <button class="search-button">search</button>
        </p>
        </div>
        <br>
        <div class="row">
        <div class="column">
            <table>
                <tbody><tr style="background-color:red" ;=""><td>Date:DD/MM/YYYY</td></tr>
                <tr style="background-color:rgb(124, 119, 119)" ;=""><td>Temperature</td></tr>
            </tbody></table>
            <div class="details">
                <table>
                    <tbody><tr><td><b>min</b></td><td><b>max</b></td></tr>
                    <tr><td>xx.xx</td><td>xx.xx</td></tr>
                    <tr><td>Pressure</td><td>xxx.xx</td></tr>
                    <tr><td>Humidity</td><td>xxx.xx</td></tr>
                </tbody></table>
            </div></div>
        <div class="column">
            <table>
                <tbody><tr style="background-color:red" ;=""><td>Date:DD/MM/YYYY</td></tr>
                <tr style="background-color:rgb(124, 119, 119)" ;=""><td>Temperature</td></tr>
            </tbody></table>
<div class="details">
  <table<tbody><tr><td><b>min</b></td><td><b>max</b></td></tr><tr><td>xx.xx</td><td>xx.xx</td></tr>
                <tr><td>Pressure</td><td>xxx.xx</td></tr>
                <tr><td>Humidity</td><td>xxx.xx</td></tr>
            </tbody></table>
        </div></div>
    <div class="column">
        <table>
            <tbody><tr style="background-color:red" ;=""><td>Date:DD/MM/YYYY</td></tr>
            <tr style="background-color:rgb(124, 119, 119)" ;=""><td>Temperature</td></tr>
        </tbody></table> <div class="details<table>
                <tbody><tr><td><b>min</b></td><td><b>max</b></td></tr>
                <tr><td>xx.xx</td><td>xx.xx</td></tr>
                <tr><td>Pressure</td><td>xxx.xx</td></tr>
                <tr><td>Humidity</td><td>xxx.xx</td></tr>
            </tbody></table>
        </div></div>
    <div class="column">
        <table>
            <tbody><tr style="background-color:red" ;=""><td>Date:DD/MM/YYYY</td></tr>
            <tr style="background-color:rgb(124, 119, 119)" ;=""><td>Temperature</td></tr>
        </tbody></table>
 <div class="details">
<table><tbody><tr><td><b>min</b></td><td><b>max</b></td></tr>
 <tr><td>xx.xx</td><td>xx.xx</td></tr>
 <tr><td>Pressure</td><td>xxx.xx</td></tr>  
  <tr><td>Humidity</td><td>xxx.xx</td></tr>
        </tbody></table>
    </div></div></div>
    
</body></html>
