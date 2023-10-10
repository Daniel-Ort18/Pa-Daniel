<?php
$arreglo1=array();
$arreglo2=array();
$arreglo3=array();

for($i=1;$i<=3;$i++){
    $val1=readline("Arreglo 1 con el valor de $i:");
    array_push($arreglo1,$val1);
}
for($j=1;$j<=4;$j++){
    $val2=readline("Arreglo 2 con el valor de $j:");
    array_push($arreglo2,$val2);
}
for($n=1;$n<=5;$n++){
    $val3=readline("Arreglo 3 con el valor de $n:");
    array_push($arreglo3,$val3);
}
$prom1 = prom($arreglo1);
$prom2 = prom($arreglo2);
$prom3 = prom($arreglo3);
$suma = $prom1 + $prom2 + $prom3;

print "El promedio del arreglo 1 es: ".$prom1."\n";
print "El promedio del arreglo 2 es: ".$prom2."\n";
print "El promedio del arreglo 3 es: ".$prom3."\n";
print "La suyma de los tres promedios es: ".$suma."\n";

function prom($array){
    $suma=0;
    foreach($array as $p){
        $suma+=$p;
    }
    $cant =count ($array);
    return $suma / $cant;
}
?>
