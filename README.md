<?php

$iPod = stripos($_SERVER['HTTP_USER_AGENT'],"iPod");
$iPhone = stripos($_SERVER['HTTP_USER_AGENT'],"iPhone");
$iPad = stripos($_SERVER['HTTP_USER_AGENT'],"iPad");
$Android= stripos($_SERVER['HTTP_USER_AGENT'],"Android");
if( $iPod || $iPhone || $iPad ){
        header('Location: https://apps.apple.com/us/app/talentlms/id1063795268');
}else if($Android){
        header('Location: https://play.google.com/store/apps/details?id=com.talentlms.android');
}
?> 
