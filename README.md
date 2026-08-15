#  <Doctype html!>

<html>
<head>
<style type="text/css">
     img {max-height: 200px;
	            max-width:200px;}
</style>
<body>
<img src="photo_2025-02-22_20-11-49.jpg"/>
<img src="photo_2025-02-22_20-11-53.jpg"/>
<img src="photo_2025-07-12_13-05-10.jpg"/>
<form action="broke the teeth" method="post"/>
  Username: <input type="text" name="username" maxlength="5" value="Enter Name Here" />
  <br/>
  Male:<input type="radio" name="gender" value="male"/>
  Female:<input type="radio" name="gender" value="Female"/>
  <br/>
  <p>Can you choose which colur you like</p>
   Red<input type="checkbox" name="colour" value="Red"/>
   Blue<input type="checkbox" name="colour" value="Blue"/>
   Green<input type="checkbox" name="colour" value="Green"/>
   White<input type="checkbox" name="colour" value="White"/>
   Pink<input type="checkbox" name="colour" value="Pink"/>
   <br/>
   <p>what do want to do today?<p>
   <select name="activities">
     <option value="teach">teach me </option>
	 <option value="comb">comb your hair </option>
	  <option value="brush">brush your teeth</option>
	   <option value="do">do your assignment </option>
   </select>
   <br/>
   <p>Tell me about yourself:</p>   
   <textarea name="bio" rows="8">
   Type something here
   </textarea>
   <br/>
   <p>Now submit a file right here</p>
   Password:<input type="password" name="password" maxlength="7"/>
   <input type="file" name="kaysfile"/>
   <br/>
   <input type="submit" value="submit!"/>
</form>
</body>
</head>
</html>
