
<html>
<head>
<title>몰</title>
</head>
<body>
<h1> 루</h1>
<script>
start = new Date()
sum = 0
data = prompt("숫자 여러개를 입력하시오.")
data = data.split(' ')
data = data.map(Number)
for (i = 0; i <=data.length - 1 ; i++){
   sum = sum + data[i]
   document.write("i is " + i + ",  data is " + data[i] + "<br>") 
   //document.write("k is "+ k +", sum is "+ sum + "<br>")

}
end = new Date()
document.write("sum is "+ sum + "<br>")
document.write("Computing Time is " + (end-start) + "ms")
</script>
</body>
</html>
