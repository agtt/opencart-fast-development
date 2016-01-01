# OpenCart-Fast-Development-Helper
OpenCart Fast Development - Function List 2.x

File Directory : system/helper/fast.php

# Load Helper 
$this->load->helper("fast");

#Load  tpl files
themeload($this->load,$this->response,$data,"example/example.tpl");
#Load Language variables

$list=array("heading_title","my_text");

getLanguage($this->language,$list,$data);

#Load post request and config variable

$list=array("examle_example","example2_example2");

getInput($this->request,$this->config,$list,$data);





