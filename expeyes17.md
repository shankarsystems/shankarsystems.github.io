---
layout: default
title: ExpEYES-17
description: "Experiments for Young Engineers and Scientists"
---


<div class="panel panel-primary my-panel" >
  <div class="panel-heading"><a href = "#">Introduction</a></div>
  <div class="panel-body">

	<div class="col-lg-6 col-md-6 col-sm-6 col-xs-6">
		<img src="http://expeyes.in/images/eyes17-nb2.png" class="img-responsive">
	</div>
	<div class="col-lg-6 col-md-6 col-sm-6 col-xs-6">
	      {% for F in site.data.expeyes %}
		       <p>{{ F.feature }}</p>
	      {% endfor %}
  </div>
  </div>
</div>

ExpEYES is from the PHOENIX project of Inter-University Accelerator Centre,New Delhi.
It is a hardware & software framework for developing science experiments, demonstrations and projects without getting in to the details of electronics or computer programming.
It converts your PC into a science laboratory. PHOENIX (Physics with Home-made Equipment and Innovative Experiments) project was started, in 2005 as a part of IUAC's outreach program, with the objectives of developing  affordable laboratory equipment and training teachers. Design of ExpEYES combines the real-time measurement capability of micro-controllers with the ease and flexibility  of Python programming language for data analysis and visualisation. It also functions as a test equipment for electronics hobbyists and engineering students.
Software for all products from PHOENIX are distributed under GNU General Public License and the hardware designs are under CERN OHL.

Join the [Phoenix Mailing List](http://www.freelists.org/list/phoenix-project) to be informed about the [Training Programs](http://www.iuac.res.in/~elab/phoenix/workshops/index.html) and new developments.




