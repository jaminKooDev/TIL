# 정규식(Regular Expression)
## 정규식 표
<table>
    <tr>
    	<th>패턴</th>
        <th>설명</th>
        <th>예제</th>
    </tr>
    <tr>
    	<td>.(점)</td>
        <td>어떤 문자 1개를 가르킨다.(\n 제외)</td>
        <td>a,d<br>
        	afffd aerd <b>aod</b>
        </td>
    </tr>
    <tr>
    	<td>*(별표)</td>
        <td>어떤 문자가 0 또는 그 이상 반복되는 것</td>
        <td>as*d<br>
        	agd aerd <b>asssssd ad</b>
        </td>
    </tr>
    <tr>
        <td>+(덧셈기호)</td>
        <td>어떤 문자가 1 또는 그 이상 반복되는 것</td>
        <td>as+b<br>
            agd ad <b>asssssd asd</b>
        </td>
    </tr>
    <tr>
        <td>^ </td>
        <td>이 패턴으로 시작해야 함</td>
        <td>
            ^ab<br>
            agd ad <b>abd absadadd</b>
        </td>
    </tr>
</table>
