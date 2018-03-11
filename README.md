# js-function
函數 

<!DOCTYPE html>
<html>
<head>
<title>first</title>
<style>
    #div1 { width: 100px; height: 200px; background: burlywood; display: none;}
</style>
<script>
    function togreen() 
    {
        document.getElementById('div1').style.display='block';
        
    }
    function tored()
    {
        document.getElementById('div1').style.display='none'
    }
</script>

</head>

<body>
    <input type = "checkbox"  onmouseover="togreen()" 
    onmouseout="tored()" />
    <div id= 'div1'>
        hahaha
    </div>
</body>
</html>
