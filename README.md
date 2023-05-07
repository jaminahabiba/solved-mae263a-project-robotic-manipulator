Download Link: https://assignmentchef.com/product/solved-mae263a-project-robotic-manipulator
<br>
<h1>                Design of a Robotic Manipulator</h1>

The goal of this project is to design a robotic manipulator using Dynamixel MX-28AR servo motors to accomplish some task defined by yourselves. Your team, with at most 4 students, will be graded upon:

Design

You are required to design a robotic manipulator, operated in 3D with at least 4 DoF, using Dynamixel MX-28AR servo motors as actuators. SolidWorks is available in <a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">SEASnet Lab</a> <a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">via remote access</a><a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">.</a> When you are designing, you can consider:

<ul>

 <li>The configuration to accomplish the task</li>

 <li>The link length constrained by the motor torque</li>

 <li>The joint angle constrained by the physical interference</li>

 <li>A gripper as the end-effector can be a bonus</li>

 <li>Prismatic joints can be a bonus</li>

 <li>Any interesting mechanisms can be a bonus</li>

</ul>




<h2>Forward Kinematics</h2>

You are required to derive the forward kinematics for your designed manipulator, from the base frame to the end-effector frame. The numerical values must <strong>not</strong> be used until the very end.

<h2>Inverse Kinematics</h2>

You are required to derive the inverse kinematics for your designed manipulator, using either algebraic or geometric method. The numerical values must <strong>not</strong> be used until the very end. Describe how you deal with multiple solutions.

<h2>Simulation</h2>

You are required to code your kinematics in MATLAB and do a simple task simulation to verify your kinematics via animation. An example is provided. Additional animation in SolidWorks is highly recommended but not required.




<h2>Report</h2>

You are required to submit a report by the midnight of Dec. 18<sup>th</sup>. The .pdf file should be emailed to the TA, along with everything you should deliver as a .zip file. The following contents can be included not necessarily in the exact order:

<ul>

 <li>Manipulator configuration to accomplish the task</li>

 <li>Design highlights and difficulties</li>

 <li>Static force analysis</li>

 <li>Derivation of kinematics</li>

 <li>Solution selection for inverse kinematics</li>

 <li>Singularity discussion</li>

 <li>Workspace analysis</li>

 <li>Task simulation</li>

 <li>Performance analysis in comparison with the commercial products</li>

 <li>Any constructive comments for the project can be a bonus</li>

 <li>An interesting team name/logo can be a bonus</li>

 <li>A well-written report can be a bonus</li>

 <li>The maximum page number is 10 <strong>excluding</strong> the cover page, references, appendix,</li>

 <li>At <strong>least</strong> 12-point font in Times New Roman</li>

</ul>

<em>Table 1: Grading Rubric. </em>

<table width="264">

 <tbody>

  <tr>

   <td width="46"><strong># </strong></td>

   <td width="157"><strong><em>Content</em></strong></td>

   <td width="60"><strong><em>Point </em></strong></td>

  </tr>

  <tr>

   <td width="46">1</td>

   <td width="157">Design</td>

   <td width="60">10%</td>

  </tr>

  <tr>

   <td width="46">2</td>

   <td width="157">Forward Kinematics</td>

   <td width="60">30%</td>

  </tr>

  <tr>

   <td width="46">3</td>

   <td width="157">Inverse Kinematics</td>

   <td width="60">30%</td>

  </tr>

  <tr>

   <td width="46">4</td>

   <td width="157">Simulation</td>

   <td width="60">10%</td>

  </tr>

  <tr>

   <td width="46">5</td>

   <td width="157">Presentation</td>

   <td width="60">10%</td>

  </tr>

  <tr>

   <td width="46">6</td>

   <td width="157">Report</td>

   <td width="60">10%</td>

  </tr>

 </tbody>

</table>




<h2>Design</h2>

You are required to design a robotic manipulator, operated in 3D with at least 4 DoF, using Dynamixel MX-28AR servo motors as actuators. SolidWorks is available in <a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">SEASnet Lab</a> <a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">via remote access</a><a href="https://www.seasnet.ucla.edu/setting-up-remoteapps-and-remote-desktop/">.</a> When you are designing, you can consider:

<ul>

 <li>The configuration to accomplish the task</li>

 <li>The link length constrained by the motor torque</li>

 <li>The joint angle constrained by the physical interference</li>

 <li>A gripper as the end-effector can be a bonus</li>

 <li>Prismatic joints can be a bonus</li>

 <li>Any interesting mechanisms can be a bonus</li>

</ul>




<h2>Forward Kinematics</h2>

You are required to derive the forward kinematics for your designed manipulator, from the base frame to the end-effector frame. The numerical values must <strong>not</strong> be used until the very end.




<h2>Inverse Kinematics</h2>

You are required to derive the inverse kinematics for your designed manipulator, using either algebraic or geometric method. The numerical values must <strong>not</strong> be used until the very end. Describe how you deal with multiple solutions.

<h2>Simulation</h2>

You are required to code your kinematics in MATLAB and do a simple task simulation to verify your kinematics via animation. An example is provided. Additional animation in SolidWorks is highly recommended but not required.

<h2>Report</h2>

You are required to submit a report by the midnight of Dec. 18<sup>th</sup>. The .pdf file should be emailed to the TA, along with everything you should deliver as a .zip file. The following contents can be included not necessarily in the exact order:

<ul>

 <li>Manipulator configuration to accomplish the task</li>

 <li>Design highlights and difficulties</li>

 <li>Static force analysis</li>

 <li>Derivation of kinematics</li>

 <li>Solution selection for inverse kinematics</li>

 <li>Singularity discussion</li>

 <li>Workspace analysis</li>

 <li>Task simulation</li>

 <li>Performance analysis in comparison with the commercial products</li>

 <li>Any constructive comments for the project can be a bonus</li>

 <li>An interesting team name/logo can be a bonus</li>

 <li>A well-written report can be a bonus</li>

 <li>The maximum page number is 10 <strong>excluding</strong> the cover page, references, appendix,</li>

 <li>At <strong>least</strong> 12-point font in Times New Roman</li>

</ul>