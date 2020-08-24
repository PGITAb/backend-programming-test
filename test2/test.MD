We have 2 slice(array) of string below

fruitList1 := []string{"apple", "orange", "banana", "pineapple"}
fruitList2 := []string{"lemon", "apple", "mango"}

Please implement a simple function in Golang to create a new slice(array) which merge the above 2 slices and contains only unique fruit name.

expected result:

fmt.Println(uniqueFruitList)
// output: ["apple" "banana" "lemon" "mango" "orange" "pineapple"]