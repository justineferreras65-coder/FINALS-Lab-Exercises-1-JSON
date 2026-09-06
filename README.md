<?php
header('Content-Type: application/json');

$student = [
    "name" => "Jutine Jay",
    "age" => 25,
    "course" => "BSIT"
];

$jsonString = json_encode($student);

echo $jsonString;
?>
