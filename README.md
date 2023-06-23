<!DOCTYPE html>
<html>
<body>	
  hi there
	<script type="text/javascript">
            window.location.href ="<?php
			
			if($_GET['linknya']<>'')
			{
			echo  $_GET['linknya'];
			} else {	
			echo 'none.html';	
			}	
				
				?>"
        </script>	
 
	
</body>
</html>

