<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Shapes</title>
		<script src="https://d3js.org/d3.v6.js"></script>  <!-- link to D3 library -->

		<style type="text/css">
			h1 {color:red;}		/* CSS styling */
			p {color:blue;}
      .paragraph {color:palevioletred;}
			.vert {color:black; font-family: Fantasy; font-size: 30px}
			.vert2 {color:green; font-family: Fantasy}
		</style>

	</head>

	<body>

		<div id='h_barchart'>
	  </div>

		<p class='vert'>State Confirm Rate by the End of the Month</p>

		<button id='March' onclick="v_bar_interact('button#March')">March</button>
		<button id='May' onclick="v_bar_interact('button#May')">May</button>
		<button id='July' onclick="v_bar_interact('button#July')">July</button>
		<button id='Sep' onclick="v_bar_interact('button#Sep')">Sep</button>
		<button id='Nov' onclick="v_bar_interact('button#Nov')">Nov</button><br>

		<div id='radio_color'>
		<p id="ratio">
				<input type="radio" id="sort" name="sort" value="name" checked="true">&nbsp;Sort by name
				<input type="radio" id="sort" name="sort" value="value">&nbsp;Sort by value<br>
		</p>
		</div>

		<script>
		    // JavaScript / D3 will go here
				var object_dataset = [
					{cx:150, cy:150, fill:`green`},
					{cx:30, cy:250, fill:`black`}
				];


      //-----------------------------------------------
      var WIDTH_v = 1200;
      var HEIGHT_v = 400;
			var margin = {top: 25, right: 0, bottom: 25, left: 50};
			var innerWidth = WIDTH_v - margin.left - margin.right;
			var innerHeight = HEIGHT_v - margin.top - margin.bottom;
      var sorted = false

      var march = [{'key': 'AL', 'value': 0.000204153, 'color': '#c03735'},
 {'key': 'AK', 'value': 0.000162669, 'color': '#c03735'},
 {'key': 'AZ', 'value': 0.00015895700000000002, 'color': '#407abb'},
 {'key': 'AR', 'value': 0.000156736, 'color': '#c03735'},
 {'key': 'CA', 'value': 0.000181083, 'color': '#407abb'},
 {'key': 'CO', 'value': 0.000456176, 'color': '#407abb'},
 {'key': 'CT', 'value': 0.00072112, 'color': '#407abb'},
 {'key': 'DE', 'value': 0.000271113, 'color': '#407abb'},
 {'key': 'NA', 'value': 0.000568191, 'color': '#407abb'},
 {'key': 'FL', 'value': 0.000254822, 'color': '#c03735'},
 {'key': 'GA', 'value': 0.000264471, 'color': '#407abb'},
 {'key': 'HI', 'value': 0.000123599, 'color': '#407abb'},
 {'key': 'ID', 'value': 0.00019025599999999998, 'color': '#c03735'},
 {'key': 'IL', 'value': 0.000398996, 'color': '#407abb'},
 {'key': 'IN', 'value': 0.00026529099999999996, 'color': '#c03735'},
 {'key': 'IA', 'value': 0.000134387, 'color': '#c03735'},
 {'key': 'KS', 'value': 0.00012769, 'color': '#c03735'},
 {'key': 'KY', 'value': 0.000107215, 'color': '#c03735'},
 {'key': 'LA', 'value': 0.000865816, 'color': '#c03735'},
 {'key': 'ME', 'value': 0.00020458099999999998, 'color': '#407abb'},
 {'key': 'MD', 'value': 0.000233721, 'color': '#407abb'},
 {'key': 'MA', 'value': 0.0012564380000000001, 'color': '#407abb'},
 {'key': 'MI', 'value': 0.000681195, 'color': '#407abb'},
 {'key': 'MN', 'value': 0.000102134, 'color': '#407abb'},
 {'key': 'MS', 'value': 0.00028459599999999997, 'color': '#c03735'},
 {'key': 'MO', 'value': 0.000194526, 'color': '#c03735'},
 {'key': 'MT', 'value': 0.000159996, 'color': '#c03735'},
 {'key': 'NE', 'value': 7.5e-05, 'color': '#c03735'},
 {'key': 'NV', 'value': 0.000328555, 'color': '#407abb'},
 {'key': 'NH', 'value': 0.00023093099999999997, 'color': '#407abb'},
 {'key': 'NJ', 'value': 0.0018729620000000002, 'color': '#407abb'},
 {'key': 'NM', 'value': 0.00011302799999999999, 'color': '#407abb'},
 {'key': 'NY', 'value': 0.003426776, 'color': '#407abb'},
 {'key': 'NC', 'value': 0.000135964, 'color': '#c03735'},
 {'key': 'ND', 'value': 0.00014303299999999998, 'color': '#c03735'},
 {'key': 'OH', 'value': 0.000165368, 'color': '#c03735'},
 {'key': 'OK', 'value': 0.00012155799999999999, 'color': '#c03735'},
 {'key': 'OR', 'value': 0.000143679, 'color': '#407abb'},
 {'key': 'PA', 'value': 0.00032455900000000003, 'color': '#407abb'},
 {'key': 'RI', 'value': 0.00038513800000000004, 'color': '#407abb'},
 {'key': 'SC', 'value': 0.000179657, 'color': '#c03735'},
 {'key': 'SD', 'value': 0.000114168, 'color': '#c03735'},
 {'key': 'TN', 'value': 0.000280707, 'color': '#c03735'},
 {'key': 'TX', 'value': 0.000109429, 'color': '#c03735'},
 {'key': 'UT', 'value': 0.000248912, 'color': '#c03735'},
 {'key': 'VT', 'value': 0.00041026400000000003, 'color': '#407abb'},
 {'key': 'VA', 'value': 0.000119501, 'color': '#407abb'},
 {'key': 'WA', 'value': 0.000646496, 'color': '#407abb'},
 {'key': 'WV', 'value': 8.09e-05, 'color': '#c03735'},
 {'key': 'WI', 'value': 0.00021125200000000002, 'color': '#407abb'},
 {'key': 'WY', 'value': 0.000162416, 'color': '#c03735'}]

      var may = [{'key': 'AL', 'value': 0.003607655, 'color': '#c03735'},
 {'key': 'AK', 'value': 0.000621971, 'color': '#c03735'},
 {'key': 'AZ', 'value': 0.0026457959999999997, 'color': '#407abb'},
 {'key': 'AR', 'value': 0.002323875, 'color': '#c03735'},
 {'key': 'CA', 'value': 0.002781291, 'color': '#407abb'},
 {'key': 'CO', 'value': 0.004531897, 'color': '#407abb'},
 {'key': 'CT', 'value': 0.011786428, 'color': '#407abb'},
 {'key': 'DE', 'value': 0.009675856, 'color': '#407abb'},
 {'key': 'NA', 'value': 0.012351417, 'color': '#407abb'},
 {'key': 'FL', 'value': 0.002580533, 'color': '#c03735'},
 {'key': 'GA', 'value': 0.004363677, 'color': '#407abb'},
 {'key': 'HI', 'value': 0.00045978699999999997, 'color': '#407abb'},
 {'key': 'ID', 'value': 0.001568494, 'color': '#c03735'},
 {'key': 'IL', 'value': 0.009384366, 'color': '#407abb'},
 {'key': 'IN', 'value': 0.005081683, 'color': '#c03735'},
 {'key': 'IA', 'value': 0.006099389, 'color': '#c03735'},
 {'key': 'KS', 'value': 0.0033261090000000003, 'color': '#c03735'},
 {'key': 'KY', 'value': 0.0021720479999999998, 'color': '#c03735'},
 {'key': 'LA', 'value': 0.008513391, 'color': '#c03735'},
 {'key': 'ME', 'value': 0.0016976489999999999, 'color': '#407abb'},
 {'key': 'MD', 'value': 0.008603664, 'color': '#407abb'},
 {'key': 'MA', 'value': 0.01408632, 'color': '#407abb'},
 {'key': 'MI', 'value': 0.006230689, 'color': '#407abb'},
 {'key': 'MN', 'value': 0.004289287, 'color': '#407abb'},
 {'key': 'MS', 'value': 0.005117015, 'color': '#c03735'},
 {'key': 'MO', 'value': 0.002022223, 'color': '#c03735'},
 {'key': 'MT', 'value': 0.00047250199999999997, 'color': '#c03735'},
 {'key': 'NE', 'value': 0.007188246, 'color': '#c03735'},
 {'key': 'NV', 'value': 0.00276512, 'color': '#407abb'},
 {'key': 'NH', 'value': 0.0033036429999999998, 'color': '#407abb'},
 {'key': 'NJ', 'value': 0.017969442, 'color': '#407abb'},
 {'key': 'NM', 'value': 0.0036359659999999996, 'color': '#407abb'},
 {'key': 'NY', 'value': 0.019002177, 'color': '#407abb'},
 {'key': 'NC', 'value': 0.0027398709999999996, 'color': '#c03735'},
 {'key': 'ND', 'value': 0.003351433, 'color': '#c03735'},
 {'key': 'OH', 'value': 0.0029970659999999996, 'color': '#c03735'},
 {'key': 'OK', 'value': 0.0016219479999999998, 'color': '#c03735'},
 {'key': 'OR', 'value': 0.000992238, 'color': '#407abb'},
 {'key': 'PA', 'value': 0.005912909, 'color': '#407abb'},
 {'key': 'RI', 'value': 0.013988621000000001, 'color': '#407abb'},
 {'key': 'SC', 'value': 0.00221298, 'color': '#c03735'},
 {'key': 'SD', 'value': 0.00560668, 'color': '#c03735'},
 {'key': 'TN', 'value': 0.003304353, 'color': '#c03735'},
 {'key': 'TX', 'value': 0.0021696529999999997, 'color': '#c03735'},
 {'key': 'UT', 'value': 0.0029735259999999998, 'color': '#c03735'},
 {'key': 'VT', 'value': 0.001565733, 'color': '#407abb'},
 {'key': 'VA', 'value': 0.005109355, 'color': '#407abb'},
 {'key': 'WA', 'value': 0.002803585, 'color': '#407abb'},
 {'key': 'WV', 'value': 0.001109842, 'color': '#c03735'},
 {'key': 'WI', 'value': 0.003130993, 'color': '#407abb'},
 {'key': 'WY', 'value': 0.0015515960000000001, 'color': '#c03735'}]

      var july = [{'key': 'AL', 'value': 0.017675042, 'color': '#c03735'},
 {'key': 'AK', 'value': 0.004927927, 'color': '#c03735'},
 {'key': 'AZ', 'value': 0.023465398999999998, 'color': '#407abb'},
 {'key': 'AR', 'value': 0.013837545, 'color': '#c03735'},
 {'key': 'CA', 'value': 0.012475481, 'color': '#407abb'},
 {'key': 'CO', 'value': 0.008023288, 'color': '#407abb'},
 {'key': 'CT', 'value': 0.013931556999999999, 'color': '#407abb'},
 {'key': 'DE', 'value': 0.015084763999999999, 'color': '#407abb'},
 {'key': 'NA', 'value': 0.017083977, 'color': '#407abb'},
 {'key': 'FL', 'value': 0.021481732000000003, 'color': '#c03735'},
 {'key': 'GA', 'value': 0.017168573, 'color': '#407abb'},
 {'key': 'HI', 'value': 0.001404788, 'color': '#407abb'},
 {'key': 'ID', 'value': 0.011326952, 'color': '#c03735'},
 {'key': 'IL', 'value': 0.014057568999999999, 'color': '#407abb'},
 {'key': 'IN', 'value': 0.009692644, 'color': '#c03735'},
 {'key': 'IA', 'value': 0.014036139, 'color': '#c03735'},
 {'key': 'KS', 'value': 0.009228321999999999, 'color': '#c03735'},
 {'key': 'KY', 'value': 0.006577473, 'color': '#c03735'},
 {'key': 'LA', 'value': 0.024625957, 'color': '#c03735'},
 {'key': 'ME', 'value': 0.0028924009999999997, 'color': '#407abb'},
 {'key': 'MD', 'value': 0.014419718, 'color': '#407abb'},
 {'key': 'MA', 'value': 0.016174531000000002, 'color': '#407abb'},
 {'key': 'MI', 'value': 0.008989915, 'color': '#407abb'},
 {'key': 'MN', 'value': 0.009520479, 'color': '#407abb'},
 {'key': 'MS', 'value': 0.019346814, 'color': '#c03735'},
 {'key': 'MO', 'value': 0.007415673, 'color': '#c03735'},
 {'key': 'MT', 'value': 0.0035685609999999996, 'color': '#c03735'},
 {'key': 'NE', 'value': 0.013319837, 'color': '#c03735'},
 {'key': 'NV', 'value': 0.015201827, 'color': '#407abb'},
 {'key': 'NH', 'value': 0.004812787, 'color': '#407abb'},
 {'key': 'NJ', 'value': 0.02037448, 'color': '#407abb'},
 {'key': 'NM', 'value': 0.009723254, 'color': '#407abb'},
 {'key': 'NY', 'value': 0.02130047, 'color': '#407abb'},
 {'key': 'NC', 'value': 0.011793383999999999, 'color': '#c03735'},
 {'key': 'ND', 'value': 0.008268356, 'color': '#c03735'},
 {'key': 'OH', 'value': 0.007667485, 'color': '#c03735'},
 {'key': 'OK', 'value': 0.009032161, 'color': '#c03735'},
 {'key': 'OR', 'value': 0.004298751, 'color': '#407abb'},
 {'key': 'PA', 'value': 0.009046016, 'color': '#407abb'},
 {'key': 'RI', 'value': 0.017888142, 'color': '#407abb'},
 {'key': 'SC', 'value': 0.017008519, 'color': '#c03735'},
 {'key': 'SD', 'value': 0.009817342, 'color': '#c03735'},
 {'key': 'TN', 'value': 0.015063462, 'color': '#c03735'},
 {'key': 'TX', 'value': 0.014771753, 'color': '#c03735'},
 {'key': 'UT', 'value': 0.012381946000000001, 'color': '#c03735'},
 {'key': 'VT', 'value': 0.002254847, 'color': '#407abb'},
 {'key': 'VA', 'value': 0.01041577, 'color': '#407abb'},
 {'key': 'WA', 'value': 0.007450663000000001, 'color': '#407abb'},
 {'key': 'WV', 'value': 0.003557186, 'color': '#c03735'},
 {'key': 'WI', 'value': 0.008949522, 'color': '#407abb'},
 {'key': 'WY', 'value': 0.004640965, 'color': '#c03735'}]

      var sep = [{'key': 'AL', 'value': 0.031565605, 'color': '#c03735'},
 {'key': 'AK', 'value': 0.012090848999999999, 'color': '#c03735'},
 {'key': 'AZ', 'value': 0.030019987999999997, 'color': '#407abb'},
 {'key': 'AR', 'value': 0.027734406, 'color': '#c03735'},
 {'key': 'CA', 'value': 0.020730673999999998, 'color': '#407abb'},
 {'key': 'CO', 'value': 0.012248521000000002, 'color': '#407abb'},
 {'key': 'CT', 'value': 0.016141758, 'color': '#407abb'},
 {'key': 'DE', 'value': 0.021168372999999997, 'color': '#407abb'},
 {'key': 'NA', 'value': 0.021715936, 'color': '#407abb'},
 {'key': 'FL', 'value': 0.032895272, 'color': '#c03735'},
 {'key': 'GA', 'value': 0.029953219, 'color': '#407abb'},
 {'key': 'HI', 'value': 0.008896991, 'color': '#407abb'},
 {'key': 'ID', 'value': 0.023529083, 'color': '#c03735'},
 {'key': 'IL', 'value': 0.02333682, 'color': '#407abb'},
 {'key': 'IN', 'value': 0.017827554, 'color': '#c03735'},
 {'key': 'IA', 'value': 0.028286852999999997, 'color': '#c03735'},
 {'key': 'KS', 'value': 0.020998423, 'color': '#c03735'},
 {'key': 'KY', 'value': 0.015408469, 'color': '#c03735'},
 {'key': 'LA', 'value': 0.036021816, 'color': '#c03735'},
 {'key': 'ME', 'value': 0.00400904, 'color': '#407abb'},
 {'key': 'MD', 'value': 0.020630434, 'color': '#407abb'},
 {'key': 'MA', 'value': 0.019168073, 'color': '#407abb'},
 {'key': 'MI', 'value': 0.013819563, 'color': '#407abb'},
 {'key': 'MN', 'value': 0.017578097, 'color': '#407abb'},
 {'key': 'MS', 'value': 0.0329923, 'color': '#c03735'},
 {'key': 'MO', 'value': 0.019122835, 'color': '#c03735'},
 {'key': 'MT', 'value': 0.012229855, 'color': '#c03735'},
 {'key': 'NE', 'value': 0.023554493, 'color': '#c03735'},
 {'key': 'NV', 'value': 0.025966217000000003, 'color': '#407abb'},
 {'key': 'NH', 'value': 0.006079233000000001, 'color': '#407abb'},
 {'key': 'NJ', 'value': 0.023110854, 'color': '#407abb'},
 {'key': 'NM', 'value': 0.014037863999999999, 'color': '#407abb'},
 {'key': 'NY', 'value': 0.023576609, 'color': '#407abb'},
 {'key': 'NC', 'value': 0.020082982, 'color': '#c03735'},
 {'key': 'ND', 'value': 0.028666959, 'color': '#c03735'},
 {'key': 'OH', 'value': 0.013173555, 'color': '#c03735'},
 {'key': 'OK', 'value': 0.022036805, 'color': '#c03735'},
 {'key': 'OR', 'value': 0.007944782, 'color': '#407abb'},
 {'key': 'PA', 'value': 0.012818243, 'color': '#407abb'},
 {'key': 'RI', 'value': 0.023361253, 'color': '#407abb'},
 {'key': 'SC', 'value': 0.028733777000000002, 'color': '#c03735'},
 {'key': 'SD', 'value': 0.025308057000000002, 'color': '#c03735'},
 {'key': 'TN', 'value': 0.02872075, 'color': '#c03735'},
 {'key': 'TX', 'value': 0.026822602999999997, 'color': '#c03735'},
 {'key': 'UT', 'value': 0.022783206, 'color': '#c03735'},
 {'key': 'VT', 'value': 0.0028077420000000002, 'color': '#407abb'},
 {'key': 'VA', 'value': 0.017371058999999998, 'color': '#407abb'},
 {'key': 'WA', 'value': 0.011748425, 'color': '#407abb'},
 {'key': 'WV', 'value': 0.008844141, 'color': '#c03735'},
 {'key': 'WI', 'value': 0.021000496, 'color': '#407abb'},
 {'key': 'WY', 'value': 0.010277162, 'color': '#c03735'}]

      var nov = [{'key': 'AL', 'value': 0.050890187, 'color': '#c03735'},
 {'key': 'AK', 'value': 0.044530412000000005, 'color': '#c03735'},
 {'key': 'AZ', 'value': 0.044900358, 'color': '#407abb'},
 {'key': 'AR', 'value': 0.052143545, 'color': '#c03735'},
 {'key': 'CA', 'value': 0.031136288999999998, 'color': '#407abb'},
 {'key': 'CO', 'value': 0.040443771, 'color': '#407abb'},
 {'key': 'CT', 'value': 0.032899175, 'color': '#407abb'},
 {'key': 'DE', 'value': 0.036614621, 'color': '#407abb'},
 {'key': 'NA', 'value': 0.030537769, 'color': '#407abb'},
 {'key': 'FL', 'value': 0.046528133, 'color': '#c03735'},
 {'key': 'GA', 'value': 0.044414073, 'color': '#407abb'},
 {'key': 'HI', 'value': 0.012870514, 'color': '#407abb'},
 {'key': 'ID', 'value': 0.056907835, 'color': '#c03735'},
 {'key': 'IL', 'value': 0.057316465999999996, 'color': '#407abb'},
 {'key': 'IN', 'value': 0.050351452000000005, 'color': '#c03735'},
 {'key': 'IA', 'value': 0.073098537, 'color': '#c03735'},
 {'key': 'KS', 'value': 0.054891097, 'color': '#c03735'},
 {'key': 'KY', 'value': 0.040074777, 'color': '#c03735'},
 {'key': 'LA', 'value': 0.049994472000000005, 'color': '#c03735'},
 {'key': 'ME', 'value': 0.008746388, 'color': '#407abb'},
 {'key': 'MD', 'value': 0.032811859, 'color': '#407abb'},
 {'key': 'MA', 'value': 0.032808401, 'color': '#407abb'},
 {'key': 'MI', 'value': 0.038945386, 'color': '#407abb'},
 {'key': 'MN', 'value': 0.05652195, 'color': '#407abb'},
 {'key': 'MS', 'value': 0.051499438, 'color': '#c03735'},
 {'key': 'MO', 'value': 0.046210210999999994, 'color': '#c03735'},
 {'key': 'MT', 'value': 0.058195434000000004, 'color': '#c03735'},
 {'key': 'NE', 'value': 0.066380515, 'color': '#c03735'},
 {'key': 'NV', 'value': 0.049403667000000005, 'color': '#407abb'},
 {'key': 'NH', 'value': 0.015440046, 'color': '#407abb'},
 {'key': 'NJ', 'value': 0.037975319, 'color': '#407abb'},
 {'key': 'NM', 'value': 0.046305636, 'color': '#407abb'},
 {'key': 'NY', 'value': 0.033312307, 'color': '#407abb'},
 {'key': 'NC', 'value': 0.03475487, 'color': '#c03735'},
 {'key': 'ND', 'value': 0.103996788, 'color': '#c03735'},
 {'key': 'OH', 'value': 0.036021849, 'color': '#c03735'},
 {'key': 'OK', 'value': 0.049973830999999996, 'color': '#c03735'},
 {'key': 'OR', 'value': 0.017884235, 'color': '#407abb'},
 {'key': 'PA', 'value': 0.028654532000000003, 'color': '#407abb'},
 {'key': 'RI', 'value': 0.053544542, 'color': '#407abb'},
 {'key': 'SC', 'value': 0.042241033, 'color': '#c03735'},
 {'key': 'SD', 'value': 0.09095482, 'color': '#c03735'},
 {'key': 'TN', 'value': 0.054837232, 'color': '#c03735'},
 {'key': 'TX', 'value': 0.044491043, 'color': '#c03735'},
 {'key': 'UT', 'value': 0.061044468, 'color': '#c03735'},
 {'key': 'VT', 'value': 0.006686015, 'color': '#407abb'},
 {'key': 'VA', 'value': 0.027864152000000003, 'color': '#407abb'},
 {'key': 'WA', 'value': 0.022582327000000003, 'color': '#407abb'},
 {'key': 'WV', 'value': 0.026695355, 'color': '#c03735'},
 {'key': 'WI', 'value': 0.070714413, 'color': '#407abb'},
 {'key': 'WY', 'value': 0.057545541, 'color': '#c03735'}]

      var vert_bardata = march;
      function sort(value) {
        if (value=='value') {

        current_bardata = vert_bardata.slice()
                          .sort((a,b) => d3.ascending(a.value, b.value));
        sorted = true
        v_change_data(current_bardata)
      } else {
        current_bardata = vert_bardata.slice()
                          .sort((a,b) => d3.ascending(a.key, b.key));
        sorted = false
        v_change_data(current_bardata)
      };
    }

			var duration = 500;

			var xScale = d3.scaleBand()
										 .domain(vert_bardata.map(d => d.key))
										 .range([0, innerWidth])
										 .paddingInner([.2]);
			var yScale = d3.scaleLinear()
										 .domain([0, d3.max(vert_bardata, d => d.value)])
										 .range([innerHeight, 0])

			var xAxis = d3.axisBottom().scale(xScale);
			var yAxis = d3.axisLeft().scale(yScale);

			// svg
      var vert_bar_svg = d3.select("body").append("svg")
            .attr("id", "vert_bar")
            .attr("width", WIDTH_v)
            .attr("height", HEIGHT_v);
			//background rectangle
			vert_bar_svg.append("rect")
		    .attr("x", "0")
		    .attr("y", "0")
		    .attr("width", WIDTH_v)
		    .attr("height", HEIGHT_v)
		    .attr("fill", "lightyellow");

			// bars
			var vert_bars = vert_bar_svg.append('g')
												.attr("id", "bars")
												.attr("transform", `translate (${margin.left}, ${margin.top})`)
												.selectAll("rect")
												.data(vert_bardata,
															d => d.key);
			vert_bars.enter().append("rect")
						.attr("x", (d, i) => xScale(d.key))
						.attr("y", d => yScale(d.value))
						.attr("width", xScale.bandwidth())
						.attr("height", d => innerHeight - yScale(d.value))
						.attr("fill", d => d.color);
			// texts

			// show axis
			vert_bar_svg.append("g")
      	.attr("class", "xAxis")
      	.attr("transform", `translate (${margin.left}, ${HEIGHT_v - margin.bottom})`)
      	.call(xAxis);
			vert_bar_svg.append("g")
      	.attr("class", "yAxis")
      	.attr("transform", `translate (${margin.left}, ${margin.top})`)
      	.call(yAxis);

			// change the dataset
			function v_change_data(new_data) {
					//change the axis generator
          // new_data = new_data.slice().sort((a,b) => d3.ascending(a.value, b.value))

          if (sorted == true) {
            new_data = new_data.slice()
                              .sort((a,b) => d3.ascending(a.value, b.value));
          } else {
            new_data = new_data.slice()
                              .sort((a,b) => d3.ascending(a.key, b.key));
          }

					xScale.domain(new_data.map(d => d.key));
					yScale.domain([0, d3.max(new_data, d => d.value)]);

					// change bars
					var vert_bars = vert_bar_svg
														.select("#bars")
														.selectAll("rect").data(new_data, d => d.key)
	        vert_bars.enter()
										.append("rect")
										.attr("x", (d, i) => xScale(d.key))
										.attr("y", d => yScale(d.value))
										.attr("width", xScale.bandwidth())
										.attr("height", d => innerHeight - yScale(d.value))
										.attr("fill", d => d.color)
										.merge(vert_bars)
										.transition().duration(duration).ease(d3.easeLinear)
	                 .attr("x", (d, i) => xScale(d.key))
	                 .attr("y", d => yScale(d.value))
	                 .attr("width", xScale.bandwidth())
	                 .attr("height", d => innerHeight - yScale(d.value))
	                 .attr("fill", d => d.color);
					vert_bars.exit()
	          .remove()
					// change texts
					// if (show_text == true) {
					// 	var vert_texts = vert_bar_svg
					// 										.select("#texts")
					// 										.selectAll("text")
					// 										.data(new_data, d => d.key)
					// 	vert_texts.enter()
					// 						.append("text")
					// 						.attr("x", (d, i) => WIDTH_v)
					// 						.attr("y", d => yScale(d.value)+25)
					// 						.text(d => d.value)
					// 						.attr("fill", "black")
					// 						.attr("text-anchor", "middle")
					// 						.attr("font-family", "sans-serif")
					// 						.attr("font-size", 5)
					// 						.merge(vert_texts)
					// 						.transition().duration(duration).ease(d3.easeLinear)
					// 						.attr("x", (d, i) => xScale(i) + 0.5*xScale.bandwidth())
					// 						.attr("y", d => yScale(d.value)+25)
					// 						.text(d => d.value)
					// 						.attr("fill", "black")
					// 						.attr("text-anchor", "middle")
					// 						.attr("font-family", "sans-serif")
					// 						.attr("font-size", d3.max([35-new_data.length,10]));
					// 	vert_texts.exit()
		      //     .remove()
					// }
					// change axis
					vert_bar_svg.select(".xAxis")
					.transition().duration(duration).ease(d3.easeLinear)
					.call(xAxis);
					vert_bar_svg.select(".yAxis")
					.transition().duration(duration).ease(d3.easeLinear)
					.call(yAxis);

          vert_bardata = new_data;
			};
			// button trigger
			function v_bar_interact(id) {
					var paraID = d3.select(id).attr("id");
					if (paraID == "March") {
							v_change_data(march); // newvalue
					}	 else if (paraID == "May") {
              v_change_data(may)
          } else if (paraID == "July") {
              v_change_data(july)
          } else if (paraID == "Sep") {
              v_change_data(sep)
          } else if (paraID == "Nov") {
              v_change_data(nov)
          }
			};

			// color radio button
			// retrieve action from radio button
			function different_sort() {
				action = d3.select(this).node().value;
				sort(action);
			};
			d3.select("div#radio_color")
  			.selectAll("input#sort")
  			.on("click", different_sort);

			// random bars
			function random_bars() {
				var len = d3.max([5, Math.floor(Math.random()*15)]) //at least 5 bars, at most 15
				var new_data = d3.range(len).map(d => Math.floor(Math.random()*100))
																		.map((value, key) => ({key, value}));
				vert_bardata = new_data
				v_change_data(vert_bardata)
			};
		</script>

	</body>

</html>
