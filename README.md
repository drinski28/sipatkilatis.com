<html>
<style type="text/css">
 }
 body{
margin:0;
padding:0;
}
div#header{
width:100%;
height:150px;
position:fixed;
z-index:100;
background-color:#F00;

 } 

div#footer{
width:100%;
height:150x;
position:fixed;
bottom:0;
background-color:#06F;
}
div#content{
background-color:#111;
width:2%;
height:2%;
position:absolute;

    }
    button {
    background-color: ;
    color: black;
    text-align: center;
    font-size: 10px;
    {
</style>
<body>
<div id="container">
    <div id="header">
        <?php include 's/header.php';?
        <label>MERON TOTAL SCORE</label>
        &nbsp&nbsp&nbsp&nbsp&nbsp  <input id=demoI type=number value=0 min=0 max=100> <button onclick="decrement2()">ERASE</><br>
        
        <button onclick="increment()">MAKAHIG</button>
        <button onclick="increment()">NAGBIBISIKLETA ANG PAA</button>
        <button onclick="increment()">BULTO KATAWAN</button>
        <button onclick="increment()">BIGAY TODO SA PATUKA</button>
        <button onclick="increment()">BAGSAK PAKPAK</button>
        <button onclick="increment()">MALAPAD DIBDIB</button>
        <button onclick="increment()">MAHABANG BUNTOT
        </button>
        <button onclick="decrement()">NANUNUKA NG HANDLER</button>
        <button onclick="decrement()">MATANGKAD</button>
        <button onclick="increment()">TUMATAKBO PAGBINITAWAN</>
        <script>
        function increment() {
        document.getElementById('demoI').stepUp(2);
        }
        function decrement() {
        document.getElementById('demoI').stepDown(2);
        
        }
        function decrement2() {
        document.getElementById('demoI').stepDown(100);
        
        }
        </script>
    </div>
    <div id="content">
    <?php include 'index.html';?>
    </div>
    <div id="footer">
        <?php include 's/footer.php';?>
        <label>WALA TOTAL SCORE</label>
   &nbsp&nbsp&nbsp&nbsp&nbsp  <input id=2demoI type=number value=0 min=0 max=100>&nbsp<button onclick="decrement3()">ERASE</><br>
      
       <button onclick="increment1()">MAKAHIG</button>
         <button onclick="increment1()">NAGBIBISIKLETA ANG PAA</button>
        <button onclick="increment1()">BULTO KATAWAN</button>
         <button onclick="increment1()">BIGAY TODO SA PATUKA</button>
        <button onclick="increment1()">BAGSAK PAKPAK</button>
        <button onclick="increment1()">MALAPAD DIBDIB</button>
        <button onclick="increment1()">MAHABANG BUNTOT</button>
        <button onclick="decrement1()">NANUNUKA NG HANDLER</button>
        <button onclick="decrement1()">MATANGKAD</button>
        <button onclick="increment1()">TUMATAKBO PAGBINITAWAN</>
        <script>
        function increment1() {
        document.getElementById('2demoI').stepUp(2);
        }
        function decrement1() {
        document.getElementById('2demoI').stepDown(2);
       
     
        
        
        }
        function decrement3() {
        document.getElementById('2demoI').stepDown(100);
        
        }
        </script>
    </div>
</div>
</body>
I have header and footer only after I clicked not in the split screen: pic2

html
css
</html>
