# assign-2
<?php

$films=array("fast","pred","persuit","prestige");
$keyword="avatar";
   	$result="yes";
   for($i=0; $i<count($films);$i++){
   if($films [$i]!=$keyword ){
   	$result="no";
   	continue;
   }
}
echo $result;

//2
   echo '<hr/>';
$films=array("avatar","pres","avatar","pres");
$keyword="avatar";
print_r(array_count_values($films));

//3
   echo '<hr/>';
$films=array("ava","pre","ava","pre");
print_r(array_reverse($films));

//4
echo '<hr/>';
$tests=array(1,"tarek",1.5,true,7,'s',false);
$keyword="true";
   	$result="no";
   for($i=0; $i<count($tests);$i++){
   if($tests [$i]==$keyword ){
   	$result="yes";
   	continue;
   }
}
 
 //5
   echo '<hr/>';
$tests=array(5,4,9,1);
echo(max(5,4,9,1));

//6
echo '<hr/>';
$tests=array(5,4,9);
echo array_sum($tests);

//7
echo'<hr/>';
$tests=array(6,4,9,3,12,8,7);
$average = array_sum($tests) / count($tests);
echo $average;

//8
echo '<hr/>';
$tests= array(6, 4, 9,3, 12,8,7);
sort($tests);
$arr = count($tests);
for($x = 0; $x < $arr; $x++) {
    echo $tests [$x];
}

echo '<hr/>';
?>

