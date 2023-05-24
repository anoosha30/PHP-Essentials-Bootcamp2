# PHP-Essentials-Bootcamp2
Assignment - PHP Essentials Bootcamp

<?php
// Function to print the multiplication table
function printMultiplicationTable($number) {
    // Iterate from 1 to 10
    for ($i = 1; $i <= 10; $i++) {
        // Calculate the product
        $product = $number * $i;
        
        // Print the multiplication table row
        echo "$number x $i = $product\n";
    }
}

// Test the function with a number
$givenNumber = 5;
printMultiplicationTable($givenNumber);
?>
