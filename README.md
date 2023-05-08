Download Link: https://assignmentchef.com/product/solved-robotics-project2-puma-560-robot-manipulator
<br>
For the PUMA 560 robot manipulator, please write a program to plan a path for both (a) Joint move and (b) Cartesian move. The starting, via, and end points for the path are

<table width="542">

 <tbody>

  <tr>

   <td width="82"> 0 −1 <em>A </em>=   00</td>

   <td width="21">1000</td>

   <td width="21">0010</td>

   <td width="123"></td>

   <td width="21">0010</td>

   <td width="33">−1000</td>

   <td width="123"></td>

   <td width="33">0−100</td>

   <td width="33">0 0−10</td>

   <td width="50">−25 <sup></sup>10 <em>,</em>−20 1</td>

  </tr>

 </tbody>

</table>

respectively. The length unit above is cm. For each move, you need to do the planning for both (a) straight line portion and (b) transition portion. The transition portion has to meet the requirement of position, velocity, and acceleration continuities with the straight line portion. Please use the method introduced in the class. For joint move, choose one configuration and derive its corresponding Cartesian path. For Cartesian move, find one feasible corresponding joint path. Please demonstrate the results by geometrical curves instead of listings of numbers. The time to move from point A to B is 0.5 sec., and from point B to C 0.5 sec. The <em>t<sub>acc </sub></em>for the transition portion is 0.2 sec. and the sampling time 0.002 sec.