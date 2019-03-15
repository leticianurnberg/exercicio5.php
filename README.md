<?php

print "Qual a distancia que deseja percorrer?";
$dis = (int) fgets (STDIN);

print "Qual a velocidade média esperada para o percurso?";
$per = (int) fgets (STDIN);

$total = $dis/$per;

print"Seu tempo de viagem será de $total horas";

