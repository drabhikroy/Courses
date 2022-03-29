---
title: "Scratching the Surface of Quasi-Experimental Designs"
linktitle: "Week 7: Scratching the Surface of Quasi-Experimental Designs"
menu:
  readings:
    parent: Readings
    weight: 7
toc: true
output:
  rmarkdown::html_document:
    toc: true
type: docs
weight: 2
---
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />

<style>
  .hvr-sweep-to-left {
    display: inline-block;
    vertical-align: middle;
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    position: relative;
    -webkit-transition-property: color;
    transition-property: color;
    -webkit-transition-duration: 0.25s;
    transition-duration: 0.25s;
  }

.hvr-sweep-to-left:before {
  content: "";
  position: absolute;
  z-index: -1;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: #175676;
    -webkit-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transform-origin: 100% 50%;
  transform-origin: 100% 50%;
  -webkit-transition-property: transform;
  transition-property: transform;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}

.hvr-sweep-to-left:hover, .hvr-sweep-to-left:focus, .hvr-sweep-to-left:active {
  color: white;
}

.hvr-sweep-to-left:hover:before, .hvr-sweep-to-left:focus:before, .hvr-sweep-to-left:active:before {
  -webkit-transform: scaleX(1);
  transform: scaleX(1);
}

td, th, tr, table {
    border: 0 !important;
    border-spacing: 0 !important;
    border-color: transparent;
  }
</style>
  
### Read The Text





<table class=" lightable-paper" style='font-family: "Arial Narrow", arial, helvetica, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;'>
 <thead>
  <tr>
   <th style="text-align:left;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Source </th>
   <th style="text-align:left;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Title </th>
   <th style="text-align:left;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Pages </th>
   <th style="text-align:center;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Assigned </th>
   <th style="text-align:center;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Read Before </th>
   <th style="text-align:center;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Required </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 15em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Leavy Chapter 4 </td>
   <td style="text-align:left;width: 20em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Quantiative Research Design </td>
   <td style="text-align:left;width: 7em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 93 - 122 </td>
   <td style="text-align:center;width: 10em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 2/22/22 </td>
   <td style="text-align:center;width: 10em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 2/28/22 </td>
   <td style="text-align:center;width: 5em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> <svg aria-hidden="true" role="img" viewbox="0 0 512 512" style="height:15px;width:15px;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:#428bca;overflow:visible;position:relative;"><path d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"></path></svg> </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 15em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Leavy Chapter 5 </td>
   <td style="text-align:left;width: 20em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Qualitative Research Design </td>
   <td style="text-align:left;width: 7em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 124 - 162 </td>
   <td style="text-align:center;width: 10em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 2/22/22 </td>
   <td style="text-align:center;width: 10em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> 2/28/22 </td>
   <td style="text-align:center;width: 5em; color: #ffffff !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> <svg aria-hidden="true" role="img" viewbox="0 0 512 512" style="height:15px;width:15px;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:#428bca;overflow:visible;position:relative;"><path d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"></path></svg> </td>
  </tr>
</tbody>
</table>

### Read A Paper



<center>
<table class=" lightable-paper" style='font-family: "Arial Narrow", arial, helvetica, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;'>
 <thead>
  <tr>
   <th style="text-align:left;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Source </th>
   <th style="text-align:center;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Link </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 30em; color: #ffffff !important;vertical-align: middle !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> Marinescu, Lawlor, &amp; Kording (2018). Quasi-experimental causality in neuroscience and behavioural research. <i>nature: human beings</i> (2). 891–898. <a href="https://doi.org/10.1038/s41562-018-0466-5" target="_blank">https://doi.org/10.1038/s41562-018-0466-5 </a> </td>
   <td style="text-align:center;width: 10em; color: #ffffff !important;vertical-align: middle !important;color: #ffffff !important;background-color: transparent !important;vertical-align: middle !important;"> <a href="/handouts/Marinescu,%20Lawlor,%20&amp;%20Kording%20(2018).pdf" target="_blank"><img src="/logos/pdf-ico.png" alt="Slack icon" width="40"></a> </td>
  </tr>
</tbody>
</table>
</center>
  
