# Training Day 1 - Java 8
Exercises  Java Lambdas

The following is a list of exercises, all the methods should be implemented with lambdas. Please create a java class with your first and last name and provide the solutions in that file, put it under the package `com.globant.tp.java`


1. Write a method that returns the average of a list of integers.
```
public Double average(List<Integer> list) {
}
```

2. Write a method that converts all strings in a list to their upper case.
```
public List<String> upperCase(List<String> list) {
}
```

3. Given a list of Strings, write a method that returns a list of all strings that start with the letter 'a' (lower case) and have exactly 3 letters. TIP: Use Java 8 Lambdas and Streams API's.
```
public List<String> search(List<String> list) {
}
```

4. Write a method that returns a comma separated string based on a given list of integers. Each element should be preceded by the letter 'e' if the number is even, and preceded by the letter 'o' if the number is odd. For example, if the input list is (3,44), the output should be 'o3,e44'.

```
public String getString(List<Integer> list) {
}
```


5. Given a list of strings, return a list where each string is replaced by 3 copies of the string concatenated together.


copies3(["a", "bb", "ccc"]) → ["aaa", "bbbbbb", "ccccccccc"]
copies3(["24", "a", ""]) → ["242424", "aaa", ""]
copies3(["hello", "there"]) → ["hellohellohello", "theretherethere"]
```
public List<String> copies3(List<String> strings) {
  
}
```

7. Given a list of strings, return a list of the strings, omitting any string that contains a "z". (Note: the str.contains(x) method returns a boolean)

```
noZ(["aaa", "bbb", "aza"]) → ["aaa", "bbb"]
noZ(["hziz", "hzello", "hi"]) → ["hi"]
noZ(["hello", "howz", "are", "youz"]) → ["hello", "are"]

public List<String> noZ(List<String> strings) {
  
}
```

8. Given a list of integers, return a list of those numbers, omitting any that are between 13 and 19 inclusive.

```
noTeen([12, 13, 19, 20]) → [12, 20]
noTeen([1, 14, 1]) → [1, 1]
noTeen([15]) → []
public List<Integer> noTeen(List<Integer> nums) {
  
}
```

9. Given a list of integers, return a list of those numbers squared and the product added to 10, omitting any of the resulting numbers that end in 5 or 6.


square56([3, 1, 4]) → [19, 11]
square56([1]) → [11]
square56([2]) → [14]
```
public List<Integer> square56(List<Integer> nums) {
  
}
```

