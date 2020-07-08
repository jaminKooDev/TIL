# C#에서 파이썬으로
<table>
    <tr>
    	<th>C#</th>
        <th>Python</th>
    </tr>
    <!-- 정규표현식 -->
    <tr>
    	<td><span style="color:#40e0d0">Regex</span> regex = new <span style="color:#40e0d0">Regex</span>(@"표현식", <span style="color:#40e0d0">RegexOptions</span>.Compiled)</td>
        <td><span style="color:#0000cd">import</span> re<br>
        	regex = <span style="color:#da70d6">re</span>.compile(r"표현식")	
        </td>
    </tr>
    <tr>
    	<td>str = regex.Replace(input, pattern)</td>
    	<td>str = re.sub(pattern, input)</td>
    </tr>
    <tr>
        <td>str.Substring(2,2)<br>
            2번째 인덱스에서 2글자</td>
        <td>str[2:4]
            2번째 인덱스글자부터 4번째 인덱스 글자 전 까지 </td>
    </tr>
</table>
