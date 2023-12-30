# Codewars

### The Supermarket Queue ([6 kyu](https://www.codewars.com/kata/57b06f90e298a7b53d000a86))
<img src="./codewars/6kyu The Supermarket Queue.jpg">

### Simple Consecutive Pairs ([7 kyu](https://www.codewars.com/kata/5a3e1319b6486ac96f000049))
<img src="./codewars/7kyu Simple Consecutive Pairs.jpg">

### Powers of i ([7 kyu](https://www.codewars.com/kata/5a97387e5ee396e70a00016d))
<img src="./codewars/7kyu Powers of i.jpg">

### Gravity Flip ([8 kyu](https://www.codewars.com/kata/5f70c883e10f9e0001c89673))
<img src="./codewars/8kyu Gravity Flip.png">

### Basic Statement Coverage in Unit Testing ([retired](https://www.codewars.com/kata/basic-statement-coverage-in-unit-testing))

Test the `count_ballot()` function thoroughly. There is nothing to return. Your function should do all the calls to the `'count_ballot()'` function needed to obtain full statement coverage for this function as listed in the problem description. This function takes one parameter - `ballot`, which is a string that contains the name of the person that was voted for.

Test coverage will be measured automatically.

`void test_count_ballot(std::string (*count_ballot)(std::string s)) {`

`count_ballot("trump & biden"); //should return "Invalid"`

`count_ballot("trump"); //should return "Trump"`

`count_ballot("biden"); //should return "Biden"`

`count_ballot("green"); //should return "Green"`

`count_ballot(""); //should return "None"`

`}`
