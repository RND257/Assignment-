<?php

function call_name(): string{
  $name = "ATUSINGUZA BRAVE";

return $name;
}

function my_age($c_year, $dob): float|int{
  $age = $c_year - $dob;
return $age;
}

function home_address(): string{
  $address = "Kampala";
  return $address;
}
print ( "Welcome home" call_name()."! <br> I am a born of 2002 and my home address is ".home_address()."<br>"."I am ".my_age(c_year: 2024, dob: 2003));
