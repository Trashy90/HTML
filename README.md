<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<meta name="author" content="Adrian Kwec">
	</head>
	<body>
		<h2>Łączenie wierszy</h2>
		<table border="1px">
			<tr>
				<th></th> <th>Poniedziałek</th> <th>Wtorek</th>
			</tr>
			<tr>
				<th>18:00</th> <td>Kręgle</td> <td>Polo</td>
			</tr>
			<tr>
				<th>20:00</th> <td colspan="2">Basen i Sauna</td>
		</table>
		<h2>Łączenie kolumn</h2>
		<table border="1px">
			<tr>
				<th></th> <th>gatunek</th>
			</tr>
			<tr>
				<th>film 1</th><th rowspan="3">animacja</th>
			</tr>
			<tr>
				<th>film 2</th>
			</tr>
			<tr>
				<th>film 3</th>
			</tr>
		</table>
		<h2>Tabela zagnieżdżona</h2>
		<table border="1px">
			<tr>
				<td>1000</td>
				<td>2000</td>
				<td>3000
					<table border="1px">
						<tr>
						<td>
						AAA
						</td>
						<td>
						BBB
						</td>
						</tr>
						<tr>
						<td>
						CCC
						</td>
						<td>
						DDD
						</td>
						</tr>
					</table>
				</td>
			</tr>
			<tr>
				<td>
				4000
				</td>
				<td>
				5000
				</td>
				<td>
				6000
				</td>
			</tr>	
		</table>
		
	</body>
</html>
