---


---

<h1 id="represent-request-for-meeting-in-calendar">Represent Request for Meeting in Calendar</h1>

<table>
<thead>
<tr>
<th>Element</th>
<th>Description</th>
<th>Type</th>
<th>Required</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>Meeting</td>
<td>Top Level</td>
<td>Meeting level Object</td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; time</td>
<td>meeting time</td>
<td>String</td>
<td>Required</td>
<td>Format is YYYY-MM-DD HH:MM:SS. Timezone is GMT.</td>
</tr>
<tr>
<td>&nbsp; &nbsp; duration</td>
<td>How long meeting lasts</td>
<td>number</td>
<td>Required</td>
<td>In minutes</td>
</tr>
<tr>
<td>&nbsp; &nbsp; description</td>
<td>Description of the meeting</td>
<td>string</td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; location</td>
<td>Location of the meeting</td>
<td>number</td>
<td>Optional</td>
<td>Default is an empty string</td>
</tr>
<tr>
<td>&nbsp; &nbsp; reminder</td>
<td>How many minutes before the meeting a reminder event should take place</td>
<td>number</td>
<td>Optional</td>
<td>Default is 10 minutes</td>
</tr>
<tr>
<td>&nbsp; &nbsp; invitees</td>
<td>List of email address of people to invite to the meeting</td>
<td>array of string</td>
<td>Optional</td>
<td>The strings should be valid email addresses. Default is an empty array.</td>
</tr>
</tbody>
</table>
