<h3> Dear IT Department,<h3> 

<h4 style="color:red"> A new ticket has been assigned to the department.<h4> 
<h5>Please see the details below:<h5> 

<table >
  <tr>
    <th style=" text-align: right">REGION</th>
    <td>: {{ doc.region }}</td>
  </tr>
  <tr>
    <th style=" text-align: right">BRANCH</th>
    <td>: {{ doc.branch_name }}</td>
  </tr>
  <tr>
    <th style=" text-align: right">TYPE</th>
    <td>: {{ doc.ticket_type_it }}</td>
  </tr>
   <tr>
    <th style=" text-align: right">ISSUE</th>
    <td>: {{ doc.desc }}</td>
  </tr>
</table>
<br>
Please take the necessary actions to resolve it as soon as possible.  
<br>
Thank you for your attention to this matter. 
<br>
<br>
Sincerely, 
<br>
<i>Branch Manager : {{ doc.full_name }}</i> 
<br>
<br>
<p><small>Email From :<a href="http://103.252.168.96:81/"> Sahayog Support System </a></small></p>