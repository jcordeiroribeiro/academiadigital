<?php
**//Handy Code Provided by STEPHENCARR.NET**$iPod = stripos($_SERVER['HTTP_USER_AGENT'],"iPod");$iPhone = stripos($_SERVER['HTTP_USER_AGENT'],"iPhone");$iPad = stripos($_SERVER['HTTP_USER_AGENT'],"iPad");$Android= stripos($_SERVER['HTTP_USER_AGENT'],"Android");
//check if user is using ipod, iphone or ipad...if( $iPod || $iPhone || $iPad ){
        //we send these people to Apple Storeheader('Location: https://apps.apple.com/us/app/talentlms/id1063795268'); // <-apple store link here}else if($Android){
        //we send these people to Android Storeheader('Location: https://play.google.com/store/apps/details?id=com.talentlms.android'); // <-android store link here}
**//Handy Code Provided by STEPHENCARR.NET**?>
