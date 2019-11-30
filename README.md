<div>
<div><center>
<table border="1" width="1024" cellspacing="0" cellpadding="5" bgcolor="#FFFFFF">
<tbody>
<tr>
<td>
<table border="0" width="100%" cellspacing="0" cellpadding="5">
<tbody>
<tr>
  
<td colspan="2">
<p><strong>&nbsp;The QWS Dataset&nbsp;</strong></p>
</td>
</tr>
<tr>
<td colspan="2">
<div><center>
<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td><a href="#About">About</a></td>
<td><a href="#Description">Description</a></td>
<td><a href="#Definitions">Definitions</a></td>
<td><a href="#Download">Download</a></td>
<td><a href="#Applications">Applications</a></td>
<td><a href="#Contact">Contact</a></td>
</tr>
</tbody>
</table>
</center></div>
</td>
</tr>
<tr id="About">
  <td colspan="2" bgcolor="#D6D6C0"><strong>&nbsp;About QWS Dataset&nbsp;</strong></td>
</tr>
<tr>
<td colspan="2">
<p>The main goal of this dataset is to offer a basis for Web Service researchers. The web services were collected using the <a href="http://www2007.org/poster968.php">Web Service Crawler Engine (WSCE)</a> and the majority of these services were obtained from public sources on the web including Universal Description, Discovery, and Integration (UDDI) registries, search engines and service portals. </p>
<p>The QWS Dataset includes a set of 2,507 web services and their <a href="#Quality_of_Web_Service_%28QWS%29_">Quality of Web Service (QWS)</a> measurements that were conducted during the year of 2008 using our web Service Broker (WSB) framework. Each row in this dataset represents a Web service and its corresponding nine QWS measurements (separated by commas). The first nine elements are QWS metrics that were measured using multiple Web service benchmark tools over a six-day period. The QWS values represent averages of the measurements collected during that period. The last two parameters represent the service name and reference to the WSDL document.</p>
</td>
</tr>
<tr  id="Description">
<td colspan="2" bgcolor="#D6D6C0">
  <div><strong>&nbsp;Description of QWS Dataset&nbsp;</strong></div>
</td>
</tr>
<tr>
<td colspan="2">Each row in the dataset corresponds to an existing Web service implementation. The dataset contains a collection of web services from our service repository that were continuously monitored for particular service qualities including:
<p><strong>&nbsp;QWS Parameters and Units&nbsp;</strong></p>
<div>
<table border="1" width="90%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div><center>
<table border="0" cellspacing="0" cellpadding="4">
<tbody>
<tr>
<td bgcolor="#5D7B9D">ID</td>
<td bgcolor="#5D7B9D">Parameter Name</td>
<td bgcolor="#5D7B9D">Description</td>
<td bgcolor="#5D7B9D">Units</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">1</td>
<td bgcolor="#F7F6F3">Response Time</td>
<td bgcolor="#F7F6F3">Time taken to send a request and receive a response</td>
<td bgcolor="#F7F6F3">ms</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">2</td>
<td bgcolor="#FFFFFF">Availability</td>
<td bgcolor="#FFFFFF">Number of successful invocations/total invocations</td>
<td bgcolor="#FFFFFF">%</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">3</td>
<td bgcolor="#F7F6F3">Throughput</td>
<td bgcolor="#F7F6F3">Total Number of invocations for a given period of time</td>
<td bgcolor="#F7F6F3">invokes/second</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">4</td>
<td bgcolor="#FFFFFF">Successability</td>
<td bgcolor="#FFFFFF">Number of response / number of request messages</td>
<td bgcolor="#FFFFFF">%</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">5</td>
<td bgcolor="#F7F6F3">Reliability</td>
<td bgcolor="#F7F6F3">Ratio of the number of error messages to total messages</td>
<td bgcolor="#F7F6F3">%</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">6</td>
<td bgcolor="#FFFFFF">Compliance</td>
<td bgcolor="#FFFFFF">The extent to which a WSDL document follows <a href="http://www.w3.org/TR/wsdl" target="_blank" rel="noopener">WSDL specification</a></td>
<td bgcolor="#FFFFFF">%</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">7</td>
<td bgcolor="#F7F6F3">Best Practices</td>
<td bgcolor="#F7F6F3">The extent to which a Web service follows <a href="http://www.ws-i.org/Profiles/BasicProfile-2_0%28WGD%29.html" target="_blank" rel="noopener">WS-I Basic Profile</a></td>
<td bgcolor="#F7F6F3">%</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">8</td>
<td bgcolor="#FFFFFF">Latency</td>
<td bgcolor="#FFFFFF">Time taken for the server to process a given request</td>
<td bgcolor="#FFFFFF">ms</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">9</td>
<td bgcolor="#F7F6F3"><a href="#Documentation">Documentation</a></td>
<td bgcolor="#F7F6F3">Measure of documentation (i.e. description tags) in WSDL</td>
<td bgcolor="#F7F6F3">%</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">10</td>
<td bgcolor="#FFFFFF"><a href="#Web_Service_Relevancy_Function_%28WsRF%29">WsRF</a></td>
<td bgcolor="#FFFFFF">Web Service Relevancy Function: a rank for Web Service Quality</td>
<td bgcolor="#FFFFFF">%</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">11</td>
<td bgcolor="#F7F6F3"><a href="#Service_Classification_">Service Classification</a></td>
<td bgcolor="#F7F6F3">Levels representing service offering qualities (1 through 4)</td>
<td bgcolor="#F7F6F3">Classifier</td>
</tr>
<tr>
<td bgcolor="#FFFFFF">12</td>
<td bgcolor="#FFFFFF">Service Name</td>
<td bgcolor="#FFFFFF">Name of the Web service</td>
<td bgcolor="#FFFFFF">None</td>
</tr>
<tr>
<td bgcolor="#F7F6F3">13</td>
<td bgcolor="#F7F6F3">WSDL Address</td>
<td bgcolor="#F7F6F3">Location of the Web Service Definition Language (WSDL) file on the Web</td>
<td bgcolor="#F7F6F3">None</td>
</tr>
</tbody>
</table>
</center></div>
</td>
</tr>
</tbody>
</table>
</div>
<p>In order, the number associated with each property corresponds to a column within the QWS dataset.</p>
</td>
</tr>
<tr>
  <td colspan="2" bgcolor="#D6D6C0"><strong>&nbsp;<a href="Definitions">Definitions&nbsp;</a></strong></td>
</tr>
<tr>
<td bgcolor="#E3E3D5" width="97%">
<p><strong>&nbsp;Documentation&nbsp;</strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td>One of the main properties of Web services is having proper documentation. The documentation QWS property provides a measure to the extent of which a Web service is self-describable and is based on examining WSDL documents including service name, description, operation name, description, message name, and message description tags.</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td bgcolor="#E3E3D5" width="97%">
<p><strong>&nbsp; Quality of Web Service (QWS)&nbsp;</strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td>Web service&rsquo;s ability to provide selective treatment to various clients in the most effective manner.</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td bgcolor="#E3E3D5" width="97%">
<p><strong>&nbsp; Web Service Relevancy Function (WsRF)&nbsp;</strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td>WsRF is used to measure the quality ranking of a Web service based on quality metrics (1 through 9 above).</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td bgcolor="#E3E3D5" width="97%">
<p><strong>&nbsp; Service Classification&nbsp;</strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td>The service classification represents various levels of service offering qualities. There are four service classifications:
<ol>
<li>Platinum (High quality)</li>
<li>Gold</li>
<li>Silver</li>
<li>Bronze (Low quality)</li>
</ol>
<p>The classification is based on the overall quality rating provided by our WsRF. Using WsRF values obtained for each Web services, we use a classification scheme to associate each Web services to a particular service group. The classification can be helpful to differentiate between various services that offer the same functionality.</p>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td id="#Download" colspan="2" bgcolor="#C6C6AA"><strong>&nbsp;Download Instructions&nbsp;</strong></td>
</tr>
<tr>
<td colspan="2">The QWS dataset is available free of charge for educational and non-commercial purposes. In exchange, we kindly request that you make available to us the results of running the QWS dataset. Please use the following references in citing the dataset:
<ul>
<li>Al-Masri, E., and Mahmoud Q. H., "Investigating web services on the world wide web", 17th international conference on World Wide Web (WWW '08), ACM, pp.795-804.<br /><br /></li>
<li>Al-Masri, E., and Mahmoud, Q. H., "Discovering the best web service", (poster) 16th International Conference on World Wide Web (WWW), 2007, pp. 1257-1258.<br /><br /></li>
<li>Al-Masri, E., and Mahmoud, Q. H., "QoS-based Discovery and Ranking of Web Services", IEEE 16th International Conference on Computer Communications and Networks (ICCCN), 2007, pp. 529-534.</li>
</ul>
<p>Downloading and using the QWS Data will indicate your acceptance to enter into a <a href="http://www.gnu.org/copyleft/gpl.html">&nbsp;GNU General Public License agreement&nbsp;</a>. Should the QWS Data be used in any scientific or educational study/research the authors will be accredited as the source of the data with any of the references listed above in citing the data. Redistribution of this data to any other third party or on the Web is not permitted.</p>
<p>Please click on the links below to download the QWS Dataset.&nbsp;</p>
<table>
<tbody>
<tr>
<td>
<div>&nbsp;</div>
<div><a href="https://qwsdata.github.io/qws/qws2.html"><strong>QWS Dataset ver 2.0 containing 2507 web services</strong></a></div>
</td>
</tr>
<tr>
<td>
<div>&nbsp;</div>
<div><a href="https://qwsdata.github.io/qws/qws1.html">QWS Dataset ver 1.0 containing 365 web services</a></div>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td id="#Applications"  colspan="2" bgcolor="#C6C6AA"><strong>&nbsp;Applications&nbsp;</strong></td>
</tr>
<tr>
<td colspan="2">
<ul>
<li>Web Service Classification</li>
<li>Web Service Composition</li>
<li>Web Service QoS Performance&nbsp;</li>
<li>Web Service QoS Prediction</li>
<li>Web Service Ranking</li>
<li>Web services Discovery</li>
<li>Web services Modeling</li>
<li>Web Services' Resource Management</li>
<li>Web Service Coordination</li>
<li>Service Orientated Analysis</li>
<li>Web Service Transaction</li>
<li>Business process Integration and Management</li>
<li>Web Service Recommender System<br /><br /></li>
</ul>
</td>
</tr>
<tr>
<td colspan="2" bgcolor="#C6C6AA"><strong>&nbsp;Contact Us&nbsp;</strong></td>
</tr>
<tr>
<td colspan="2">
<div>&nbsp;</div>
<div>Your comments and suggestions are welcome.</div>
<div>&nbsp;</div>
<div>Please send your comments by email: Eyhab Al-Masri (qwsdata[AT]yahoo.com)</div>
<p>&nbsp;</p>
<p>&nbsp;Copyright (c) 2007-present QWS Dataset, University of Guelph&nbsp;</p>
<p>&nbsp;<a href="https://qwsdata.github.io/qws/">https://qwsdata.github.io/qws/</a></p>
<p>&nbsp;</p>
<div><em>Last modified November 2019<br /></em></div>
<div><em>&nbsp;</em></div>
<div><em>&nbsp;</em></div>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
</center></div>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
</div>
