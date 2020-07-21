# C#에서 파이썬으로

|C#|Python|
|---|---|
|Regex regex = new Regex(@"표현식", RegexOptions.Compiled)|import re<br>regex = re.compile(r"표현식")|
|str = regex.Replace(input, pattern)|str = re.sub(pattern, input)|
|tr.Substring(2,2)<br>2번째 인덱스에서 2글자|str[2:4]<br>2번째 인덱스글자부터 4번째 인덱스 글자 전 까지|
|str.Indexof("string")|str.find("string")|
|str = regex.Replace(input, pattern, replacement)|str = re.sub(pattern, replacement, input)|
|m.Value|m.group()|
