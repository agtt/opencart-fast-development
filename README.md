# OpenCart-Fast-Development-Helper
OpenCart Fast Development - Function List 2.x

File Directory : system/helper/fast.php

# Load Helper 
$this->load->helper("fast");

# Use Functions 
Load  tpl files

themeload($this->load,$this->response,$data,"example/example.tpl");

Load Language variable

$list=array("heading_title","my_text");
getLanguage($this->language,$list,$data);





