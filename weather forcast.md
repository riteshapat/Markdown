---


---

<h1 id="represent-the-weather-forecast-for-one-day">Represent the weather forecast for one Day</h1>

<table>
<thead>
<tr>
<th>Element</th>
<th>Description</th>
<th>Type</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>longitude</td>
<td>longitude of the location where forecast will take place</td>
<td>number</td>
<td></td>
</tr>
<tr>
<td>latitude</td>
<td>latitude of the location where forecast will take place</td>
<td>number</td>
<td></td>
</tr>
<tr>
<td>forecast</td>
<td>Daily forecast</td>
<td>array of daily forecast</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp;date</td>
<td>weather date</td>
<td>String</td>
<td>format is YYYY-MM-DD</td>
</tr>
<tr>
<td>&nbsp;&nbsp;description</td>
<td>Text description for the weather</td>
<td>String</td>
<td>values can be “sunny”,“overcast”,“partly cloud”,“raining” and “snowing”</td>
</tr>
<tr>
<td>&nbsp;&nbsp;maxTemp</td>
<td>High Temperature</td>
<td>Integer</td>
<td>in degree Celsius</td>
</tr>
<tr>
<td>&nbsp;&nbsp;minTemp</td>
<td>Low Temperature</td>
<td>Integer</td>
<td>in degree Celsius</td>
</tr>
<tr>
<td>&nbsp;&nbsp;Windspeed</td>
<td>wind speed</td>
<td>Integer</td>
<td>in kilometer per hour</td>
</tr>
<tr>
<td>&nbsp;&nbsp;danger</td>
<td>True if weather condition is worst or false</td>
<td>Boolean</td>
<td></td>
</tr>
</tbody>
</table>
