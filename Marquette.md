# Marquette High School
![Web image](https://soccerstl.net/wp-content/uploads/2018/04/marquette-mustangs-logo.jpg)

[Marquette Homepage](https://www.rsdmo.org/marquette/Pages/default.aspx)

```python
  fact = "This is where I found my love for coding"
  print(fact)
```
 
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {

        if(i%3==0 && i%5==0)
            {
                displayHTML+="<p>"+"FizzBuzz"+"</p>";
            }
        else if(i%5==0)
            {
                displayHTML+="<p>"+"Buzz"+"</p>";
            }
        else if(i%3==0)
            {
                displayHTML+="<p>"+"Fizz"+"</p>";
            }
        else displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
