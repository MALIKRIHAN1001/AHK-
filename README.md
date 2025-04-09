<html>
<body bgcolor="yellow">
<form action="/action_page.php">
<h1><font color="blue"><b>Application form for Addmission of ITI-2025</b></h1></font>

<b>Enter Student photo:</b><br>
<input type="file"><br>

<b>Enter Student name:</b><br>
<input type="text"><br>

<b>Enter Student Father name:</b><br>
<input type="text"><br>

<b>Enter Student DOB:</b><br>
<input type="date"><br>

<b>Enter your address:</b><br>
<textarea rows="5" cols="80">
</textarea><br>

<b>Enter Student MobileNo:<b><br>
<input type="text"><br>

<b>Enter Student E-mail Id:<b><br>
<input type="E-mail"><br>

<b>Enter Student UID(Aadhar No):<b><br>
<input type="number"><br><br>

<b>Select Your Gender:</b><br>
<input type="radio" value="Male" name="G">Male<br>
<input type="radio" value="Female" name="G">Female<br><br>

<b>Select Your Catagory:</b><br>
<input type="radio" value="sc" name="C">sc<br>
<input type="radio" value="st" name="C">st<br>
<input type="radio" value="Other" name="C">Other<br><br>

<b>Select Your Qulification:</b><br>
<input type="checkbox" value="SSLC" name="Q">SSLC<br>
<input type="checkbox" value="PUC" name="Q">PUC<br>
<input type="checkbox" value="Any Degree" name="Q">Any Degree<br><br>

<b>Enter Student SSLC obtianed Marks:</b><br>
<input type="text" id="m"><br>
percentege:<br>
<input type="text" id="p"><br>
<input type="button" onclick="cal()" value="cal per"/><br><br>

Select Your following option:<br>
<input type="radio" value="Rural 10%" id="r" name="G">Rural 10% onclick="Rul()"<br>
<input type="radio" value="Urbun 0%" id="u"  name="G">Urbun 0% onclick="url()"<br>

Revised Percentage:<br>
<input type="text"><br>

Select Your Trade:<br>
<select>
<option value="COPA">COPA</option>
<option value="ELE">ELE</option>
<option value="FITER">FITER</option>
<option value="TERNAR">TERNAR</option>
</select><br>
<input type="submit" value="submit">
<input type="reset" value="reset">
</form>

<script>
function cal()
{
var m=document.ap.m.value;
var p=(m/600)*100;
document.ap.p.value=p;
}
</script>
</body>
</html>
