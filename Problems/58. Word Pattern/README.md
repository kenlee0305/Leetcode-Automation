# 58. Word Pattern
### Difficulty: Easy
Given a pattern and a string s, find if s follows the same pattern. <br/> Here follow means a full match, such that there is a bijection between a letter in pattern and a non-empty word in s. <br/>   <br/><b>- Example</b> 1: <br/> Input: pattern = "abba", s = "dog cat cat dog" <br/> Output: true <br/> <br/><b>- Example</b> 2: <br/> Input: pattern = "abba", s = "dog cat cat fish" <br/> Output: false <br/> <br/><b>- Example</b> 3: <br/> Input: pattern = "aaaa", s = "dog cat cat dog" <br/> Output: false <br/> <br/><b>- Example</b> 4: <br/> Input: pattern = "abba", s = "dog dog dog dog" <br/> Output: false <br/>   Constraints: <br/> 1 <= pattern.length <= 300 <br/> pattern contains only lower-case English letters. <br/> 1 <= s.length <= 3000 <br/> s contains only lower-case English letters and spaces ' '. <br/> s does not contain any leading or trailing spaces. <br/> All the words in s are separated by a single space.