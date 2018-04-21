# RR-machine
<html class=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<meta http-equiv="Cache-Control" content="no-store">
		<title>Инфо</title>
	 	<script type="text/javascript" src="//static.rivalregions.com/static/js/jquery-latest.js"></script>
		<script type="text/javascript" src="//static.rivalregions.com/static/js/jquery.tablesorter.min.js"></script>
		<style>
		th, td{
			font-family: Calibri, Tahoma;
			font-size: 11px;
			border: 1px solid #EEE;
		}
		th{
			cursor: pointer;
			font-weight: bold;
			background-color: #F0F0F0;
		}
		th:hover{
			color: #3c6ae0;
		}
		tr.odd{
		    background-color:#e0f0f8;
		}
		</style>
		<script>
		$(document).ready(function() 
		    { 
		        $("table").tablesorter({
				   widgets: ['zebra'],
				   widgetZebra: {css: ["odd","even"]}
				}); 
		    } 
		); 
		</script>
		<link type="text/css" rel="stylesheet" charset="UTF-8" href="https://translate.googleapis.com/translate_static/css/translateelement.css"></head><body><table cellspacing="0">
		<thead>
			<tr>
				<th class="header">РЕГИОН</th>
				<th title="Автономия" class="header">АВТ</th>
				<th title="Население" class="header">НАС</th>
				<th title="Прописанные" class="header">ПРО</th>
				<th title="Начальный урон атаки" class="header">ВА</th>
				<th title="Начальный урон защиты" class="header">УЗ</th>
				<th title="Уровень строения Госпиталь" class="header">ГО</th>
				<th title="Уровень строения Военная база" class="header">ВО</th>
				<th title="Уровень строения Школа" class="header">ШК</th>
				<th title="Уровень строения ПВО" class="header">ПВ</th>
				<th title="Уровень строения Порт" class="header">ПО</th>
				<th title="Уровень строения Электростанция" class="header">ЭЛ</th>
				<th title="Уровень строения Космодром" class="header">КО</th>
				<th title="Уровень строения Аэродром" class="header">АЭ</th>
				<th title="Уровень строения Жилищный фонд" class="header">ЖФ</th>

				<th title="Ресурсы, текущие" style="color: #858300;" class="header">ЗОЛ</th>
				<th title="Ресурсы, текущие" class="header">НЕФ</th>
				<th title="Ресурсы, текущие" style="color: #851300;" class="header">РУД</th>
				<th title="Ресурсы, текущие" class="header">УРА</th>
				<th title="Ресурсы, текущие" class="header">АЛМ</th>


				<th title="Ресурсы, реальные" style="color: #858300;" class="header">ЗОЛ&nbsp;Р</th>
				<th title="Ресурсы, реальные" class="header">НЕФ&nbsp;Р</th>
				<th title="Ресурсы, реальные" style="color: #851300;" class="header">РУД&nbsp;Р</th>
				<th title="Ресурсы, реальные" class="header">УРА&nbsp;Р</th>
				<th title="Ресурсы, реальные" class="header">АЛМ&nbsp;Р</th>


				<th title="Ресурсы, включая Глубокую Разведку" style="color: #858300;" class="header">ЗОЛ&nbsp;В</th>
				<th title="Ресурсы, включая Глубокую Разведку" class="header">НЕФ&nbsp;В</th>
				<th title="Ресурсы, включая Глубокую Разведку" style="color: #851300;" class="header">РУД&nbsp;В</th>
				<th title="Ресурсы, включая Глубокую Разведку" class="header">УРА&nbsp;В</th>
				<th title="Ресурсы, включая Глубокую Разведку" class="header">АЛМ&nbsp;В</th>

				<th title="Индекс образования" class="header">ИНД&nbsp;О</th>
				<th title="Военный индекс" class="header">ИНД&nbsp;В</th>
				<th title="Индекс медицины" class="header">ИНД&nbsp;М</th>
				<th title="Индекс развития" class="header">ИНД&nbsp;Р</th>

				<th title="Налоги на доход" class="header">%</th>
				<th title="Налоги на продажу" class="header">%&nbsp;ПРО</th>
				<th title="Налоги на доход частных фабрик" class="header">%&nbsp;ФАБ</th>
				<th title="Налоги на доход частных фабрик: Руда" class="header">%&nbsp;ФАБ&nbsp;РУД</th>
				<th title="Налоги на доход частных фабрик: Нефть" class="header">%&nbsp;ФАБ&nbsp;НЕФ</th>
				<th title="Налоги на доход частных фабрик: Уран" class="header">%&nbsp;ФАБ&nbsp;УРА</th>
				<th title="Налоги на доход частных фабрик: Алмазы" class="header">%&nbsp;ФАБ&nbsp;АЛМ</th>

				<th title="Доля в бюджет для региональных фабрик: Нефть" class="header">РАБ&nbsp;НЕФ</th>
				<th title="Доля в бюджет для региональных фабрик: Руда" class="header">РАБ&nbsp;РУД</th>
				
									<th title="Число фабрик в регионе" class="header">НЕФ</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">НЕФ&nbsp;ТОП</th>
										<th title="Число фабрик в регионе" class="header">РУД</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">РУД&nbsp;ТОП</th>
										<th title="Число фабрик в регионе" class="header">УРА</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">УРА&nbsp;ТОП</th>
										<th title="Число фабрик в регионе" class="header">AЛМ</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">AЛМ&nbsp;ТОП</th>
										<th title="Число фабрик в регионе" class="header">КИС</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">КИС&nbsp;ТОП</th>
										<th title="Число фабрик в регионе" class="header">ЗОЛ</th>
					<th title="Максимальный уровень фабрики в регионе" class="header">ЗОЛ&nbsp;ТОП</th>
								</tr>
		</thead>
					<tbody><tr class="even">
				<td>Юго-центральная&nbsp;Болгария,&nbsp;id:&nbsp;2406</td>
				<td>да</td>
				<td>19</td>
				<td>9</td>
				<td>8550000</td>
				<td>147050000</td>
				<td>420</td>
				<td>300</td>
				<td>200</td>
				<td>250</td>
				<td>0</td>
				<td>1100</td>
				<td>50</td>
				<td>150</td>
				<td>5620</td>

				<td style="color: #858300;">338.625
				</td><td>258.022
				</td><td style="color: #851300;">226.97</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">391</td>
				<td>261</td>
				<td style="color: #851300;">230</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">391</td>
				<td>261</td>
				<td style="color: #851300;">230</td>
				<td>2</td>
				<td>2</td>

				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>7</td>

				<td>5</td>
				<td>0</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>

				<td>5</td>
				<td>1</td>
				
									<td>1</td>
					<td>8</td>
										<td>1</td>
					<td>51</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>4</td>
					<td>150</td>
						
			</tr>
						<tr class="odd">
				<td>Северные&nbsp;Нидерланды,&nbsp;id:&nbsp;4001</td>
				<td>да</td>
				<td>36</td>
				<td>31</td>
				<td>67950000</td>
				<td>523800000</td>
				<td>1210</td>
				<td>900</td>
				<td>700</td>
				<td>1800</td>
				<td>2300</td>
				<td>1100</td>
				<td>7</td>
				<td>200</td>
				<td>5620</td>

				<td style="color: #858300;">0
				</td><td>127.331
				</td><td style="color: #851300;">245.306</td>
				<td>2</td>
				<td>22.831</td>


				<td style="color: #858300;">379</td>
				<td>223</td>
				<td style="color: #851300;">247</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">379</td>
				<td>223</td>
				<td style="color: #851300;">247</td>
				<td>2</td>
				<td>27</td>

				<td>7</td>
				<td>9</td>
				<td>6</td>
				<td>7</td>

				<td>2</td>
				<td>0</td>
				<td>0</td>
				<td>0</td>
				<td>0</td>
				<td>0</td>
				<td>0</td>

				<td>20</td>
				<td>20</td>
				
									<td>2</td>
					<td>136</td>
										<td>1</td>
					<td>53</td>
										<td>0</td>
					<td>0</td>
										<td>2</td>
					<td>149</td>
										<td>0</td>
					<td>0</td>
										<td>10</td>
					<td>150</td>
						
			</tr>
						<tr class="even">
				<td>Восточные&nbsp;Нидерланды,&nbsp;id:&nbsp;4002</td>
				<td>да</td>
				<td>69</td>
				<td>32</td>
				<td>44100000</td>
				<td>326000000</td>
				<td>1010</td>
				<td>600</td>
				<td>600</td>
				<td>1000</td>
				<td>600</td>
				<td>1100</td>
				<td>28</td>
				<td>100</td>
				<td>5620</td>

				<td style="color: #858300;">249.206
				</td><td>227.675
				</td><td style="color: #851300;">249.186</td>
				<td>1.809</td>
				<td>2</td>


				<td style="color: #858300;">359</td>
				<td>266</td>
				<td style="color: #851300;">250</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">359</td>
				<td>266</td>
				<td style="color: #851300;">250</td>
				<td>2</td>
				<td>2</td>

				<td>7</td>
				<td>6</td>
				<td>5</td>
				<td>7</td>

				<td>7</td>
				<td>0</td>
				<td>8</td>
				<td>8</td>
				<td>8</td>
				<td>8</td>
				<td>8</td>

				<td>20</td>
				<td>20</td>
				
									<td>2</td>
					<td>139</td>
										<td>1</td>
					<td>73</td>
										<td>1</td>
					<td>69</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>6</td>
					<td>163</td>
						
			</tr>
						<tr class="odd">
				<td>Западные&nbsp;Нидерланды,&nbsp;id:&nbsp;4003</td>
				<td>нет</td>
				<td>62</td>
				<td>91</td>
				<td>140850000</td>
				<td>813950000</td>
				<td>1605</td>
				<td>1050</td>
				<td>1050</td>
				<td>2500</td>
				<td>2500</td>
				<td>1200</td>
				<td>7</td>
				<td>2500</td>
				<td>5620</td>

				<td style="color: #858300;">0
				</td><td>209.863
				</td><td style="color: #851300;">185.551</td>
				<td>1.988</td>
				<td>1.571</td>


				<td style="color: #858300;">372</td>
				<td>296</td>
				<td style="color: #851300;">230</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">372</td>
				<td>296</td>
				<td style="color: #851300;">230</td>
				<td>2</td>
				<td>2</td>

				<td>10</td>
				<td>10</td>
				<td>10</td>
				<td>7</td>

				<td>5</td>
				<td>0</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>

				<td>20</td>
				<td>20</td>
				
									<td>5</td>
					<td>79</td>
										<td>1</td>
					<td>12</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>27</td>
					<td>158</td>
						
			</tr>
						<tr class="even">
				<td>Южные&nbsp;Нидерланды,&nbsp;id:&nbsp;4004</td>
				<td>да</td>
				<td>38</td>
				<td>48</td>
				<td>81450000</td>
				<td>338950000</td>
				<td>950</td>
				<td>500</td>
				<td>650</td>
				<td>850</td>
				<td>300</td>
				<td>1000</td>
				<td>25</td>
				<td>375</td>
				<td>5620</td>

				<td style="color: #858300;">0
				</td><td>294.672
				</td><td style="color: #851300;">203.281</td>
				<td>2</td>
				<td>1.901</td>


				<td style="color: #858300;">366</td>
				<td>296</td>
				<td style="color: #851300;">211</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">366</td>
				<td>296</td>
				<td style="color: #851300;">211</td>
				<td>2</td>
				<td>2</td>

				<td>7</td>
				<td>4</td>
				<td>4</td>
				<td>7</td>

				<td>5</td>
				<td>0</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>

				<td>0</td>
				<td>20</td>
				
									<td>4</td>
					<td>50</td>
										<td>3</td>
					<td>52</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>0</td>
					<td>0</td>
										<td>13</td>
					<td>159</td>
						
			</tr>
						<tr class="odd">
				<td>Фламандский&nbsp;регион,&nbsp;id:&nbsp;4101</td>
				<td>да</td>
				<td>72</td>
				<td>85</td>
				<td>164250000</td>
				<td>457550000</td>
				<td>1033</td>
				<td>560</td>
				<td>589</td>
				<td>1200</td>
				<td>500</td>
				<td>1100</td>
				<td>14</td>
				<td>310</td>
				<td>5620</td>

				<td style="color: #858300;">0
				</td><td>215.494
				</td><td style="color: #851300;">225.3</td>
				<td>1.999</td>
				<td>1.225</td>


				<td style="color: #858300;">288</td>
				<td>242</td>
				<td style="color: #851300;">247</td>
				<td>2</td>
				<td>2</td>


				<td style="color: #858300;">288</td>
				<td>242</td>
				<td style="color: #851300;">247</td>
				<td>2</td>
				<td>2</td>

				<td>6</td>
				<td>5</td>
				<td>5</td>
				<td>7</td>

				<td>5</td>
				<td>0</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>
				<td>15</td>

				<td>50</td>
				<td>50</td>
				
									<td>4</td>
					<td>66</td>
										<td>2</td>
					<td>126</td>
										<td>0</td>
					<td>0</td>
										<td>2</td>
					<td>70</td>
										<td>1</td>
					<td>1</td>
										<td>19</td>
					<td>157</td>
						
			</tr>
					</tbody></table><div id="goog-gt-tt" class="skiptranslate" dir="ltr"><div style="padding: 8px;"><div><div class="logo"><img src="https://www.gstatic.com/images/branding/product/1x/translate_24dp.png" width="20" height="20" alt="Google Translate"></div></div></div><div class="top" style="padding: 8px; float: left; width: 100%;"><h1 class="title gray">Oorspronkelijke tekst</h1></div><div class="middle" style="padding: 8px;"><div class="original-text"></div></div><div class="bottom" style="padding: 8px;"><div class="activity-links"><span class="activity-link">Een betere vertaling bijdragen</span><span class="activity-link"></span></div><div class="started-activity-container"><hr style="color: #CCC; background-color: #CCC; height: 1px; border: none;"><div class="activity-root"></div></div></div><div class="status-message" style="display: none;"></div></div>
		<div class="goog-te-spinner-pos"><div class="goog-te-spinner-animation"><svg xmlns="http://www.w3.org/2000/svg" class="goog-te-spinner" width="96px" height="96px" viewBox="0 0 66 66"><circle class="goog-te-spinner-path" fill="none" stroke-width="6" stroke-linecap="round" cx="33" cy="33" r="30"></circle></svg></div></div></body></html>
