<p></p>
<div align="center">
<table id="table1" border="1" width="800" cellspacing="0" cellpadding="5" bgcolor="#FFFFFF">
<tbody>
<tr>
<td>
<table id="table2" border="0" width="100%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td colspan="2">
<p align="center"><strong> <span style="color: #808080; font-family: Verdana; font-size: x-large;"> The QWS Dataset </span> </strong></p>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2">
<div align="center">
<table id="table7" border="0" width="80%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#About_"> About </a> </span></td>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#Description_">Description</a> </span></td>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#Definitions">Definitions</a> </span></td>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#Download_0">Download</a> </span></td>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#Applications_">Applications</a> </span></td>
<td align="center"><span style="font-family: Verdana; font-size: small;"> <a href="#Contact_Us">Contact</a> </span></td>
</tr>
</tbody>
</table>
</div>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#D6D6C0"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="About_"></a> About QWS Dataset </span> </strong></td>
</tr>
<tr>
<td colspan="2">
<p align="justify"><span style="font-family: Arial; font-size: small;"> The main goal of this dataset is to offer a basis for Web Service researchers. To this end, this dataset contains 2507 web services and their QoS measurements. The services were collected using my </span> <span style="color: #ffffff; font-family: Arial; font-size: small;"> <a href="http://www2007.org/poster968.php">Web Service Crawler Engine (WSCE)</a>. </span><span style="font-family: Arial; font-size: small;"> The majority of Web services were obtained from public sources on the Web including Universal Description, Discovery, and Integration (UDDI) registries, search engines, and service portals. The QWS Dataset includes a set of 2,507 Web services and their <a href="#Quality_of_Web_Service_(QWS)_">Quality of Web Service (QWS)</a> measurements that were conducted during the year of 2008 using our Web Service Broker (WSB) framework. Each row in this dataset represents a Web service and its corresponding nine QWS measurements (separated by commas). The first nine elements are QWS metrics that were measured using multiple Web service benchmark tools over a six-day period. The QWS values represent averages of the measurements collected during that period. The last two parameters represent the service name and reference to the WSDL document. </span></p>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#D6D6C0"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="Description_"></a>Description of QWS Dataset </span> </strong></td>
</tr>
<tr>
<td colspan="2"><span style="font-family: Arial; font-size: small;"> Each row in the dataset corresponds to an existing Web service implementation. The dataset contains a collection of web services from our service repository that were continuously monitored for particular service qualities including: </span>
<p align="center"><strong> <span style="font-family: Arial; font-size: small;">QWS Parameters and Units</span> </strong></p>
<div align="center">
<table id="table8" border="1" width="95%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td>
<div align="center">
<table id="table9" border="0" width="100%" cellspacing="0" cellpadding="4">
<tbody>
<tr>
<td align="center" bgcolor="#5D7B9D" width="37"><span style="color: #ffffff; font-family: Arial; font-size: small;">ID</span></td>
<td align="center" bgcolor="#5D7B9D" width="153"><span style="color: #ffffff; font-family: Arial; font-size: small;"> Parameter&nbsp; Name </span></td>
<td align="center" bgcolor="#5D7B9D"><span style="color: #ffffff; font-family: Arial; font-size: small;"> Description </span></td>
<td align="center" bgcolor="#5D7B9D"><span style="color: #ffffff; font-family: Arial; font-size: small;">Units</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">1</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;">Response Time</span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Time taken to send a request and receive a response </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">ms</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">2</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;">Availability</span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> Number of successful invocations/total invocations </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">3</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;">Throughput</span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Total Number of invocations for a given period of time </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">invokes/second</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">4</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;">Successability</span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> Number of response / number of request messages </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">5</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;">Reliability</span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Ratio of the number of error messages to total messages </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">6</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;">Compliance</span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> The extent to which a WSDL document follows <a href="http://www.w3.org/TR/wsdl" target="_blank" rel="noopener">WSDL specification</a> </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">7</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;">Best Practices</span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> The extent to which a Web service follows <a href="http://www.ws-i.org/Profiles/BasicProfile-2_0(WGD).html" target="_blank" rel="noopener">WS-I Basic Profile</a> </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">8</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;">Latency</span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> Time taken for the server to process a given request </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">ms</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">9</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;"> <a href="#Documentation">Documentation</a> </span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Measure of documentation (i.e. description tags) in WSDL </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">10</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;"> <a href="#Web_Service_Relevancy_Function_(WsRF)">WsRF</a> </span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> Web Service Relevancy Function: a rank for Web Service Quality </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">%</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">11</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;"> <a href="#Service_Classification_"> Service Classification </a> </span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Levels representing service offering qualities (1 through 4) </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">Classifier</span></td>
</tr>
<tr>
<td align="center" bgcolor="#FFFFFF" width="37"><span style="font-family: Arial; font-size: small;">12</span></td>
<td bgcolor="#FFFFFF" width="153"><span style="font-family: Arial; font-size: small;">Service Name</span></td>
<td bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;"> Name of the Web service </span></td>
<td align="center" bgcolor="#FFFFFF"><span style="font-family: Arial; font-size: small;">None</span></td>
</tr>
<tr>
<td align="center" bgcolor="#F7F6F3" width="37"><span style="font-family: Arial; font-size: small;">13</span></td>
<td bgcolor="#F7F6F3" width="153"><span style="font-family: Arial; font-size: small;">WSDL Address</span></td>
<td bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;"> Location of the Web Service Definition Language (WSDL) file on the Web </span></td>
<td align="center" bgcolor="#F7F6F3"><span style="font-family: Arial; font-size: small;">None</span></td>
</tr>
</tbody>
</table>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<p><span style="font-family: Arial; font-size: small;"> In order, the number associated with each property corresponds to a column within the QWS dataset. </span></p>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#D6D6C0"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="Definitions"></a>Definitions </span> </strong></td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td bgcolor="#E3E3D5">&nbsp;</td>
<td bgcolor="#E3E3D5" width="97%">
<p align="justify"><strong> <span style="color: #0000ff; font-family: Arial; font-size: small;"> <a name="Documentation"></a>Documentation </span> </strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table id="table6" border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td width="21">&nbsp;</td>
<td><span style="font-family: Arial; font-size: small;"> One of the main properties of Web services is having proper documentation. The documentation QWS property provides a measure to the extent of which a Web service is self-describable and is based on examining WSDL documents including service name, description, operation name, description, message name, and message description tags. </span></td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="2" bgcolor="#008000"><img src="pixel.gif" width="1" height="1" border="0" /></td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td bgcolor="#E3E3D5">&nbsp;</td>
<td bgcolor="#E3E3D5" width="97%">
<p align="justify"><span style="color: #0000ff; font-family: Arial; font-size: small;"> <strong> <a name="Quality_of_Web_Service_(QWS)_"></a> Quality of Web Service (QWS) </strong> </span></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table id="table3" border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td width="21">&nbsp;</td>
<td><span style="font-family: Arial; font-size: small;"> Web service&rsquo;s ability to provide selective treatment to various clients in the most effective manner. </span></td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="2" bgcolor="#008000"><img src="pixel.gif" width="1" height="1" border="0" /></td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td bgcolor="#E3E3D5">&nbsp;</td>
<td bgcolor="#E3E3D5" width="97%">
<p align="justify"><strong> <span style="color: #0000ff; font-family: Arial; font-size: small;"> <a name="Web_Service_Relevancy_Function_(WsRF)"></a> Web Service Relevancy Function (WsRF) </span> </strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table id="table4" border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td width="21">&nbsp;</td>
<td><span style="font-family: Arial; font-size: small;"> WsRF is used to measure the quality ranking of a Web service based on quality metrics (1 through 9 above). </span></td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="2" bgcolor="#008000"><img src="pixel.gif" width="1" height="1" border="0" /></td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td bgcolor="#E3E3D5">&nbsp;</td>
<td bgcolor="#E3E3D5" width="97%">
<p align="justify"><strong> <a name="Service_Classification_"></a> <span style="color: #0000ff; font-family: Arial; font-size: small;"> Service Classification </span> </strong></p>
</td>
</tr>
<tr>
<td colspan="2" width="99%">
<table id="table5" border="0" width="100%" cellspacing="0" cellpadding="3">
<tbody>
<tr>
<td width="21">&nbsp;</td>
<td><span style="font-family: Arial; font-size: small;"> The service classification represents various levels of service offering qualities. There are four service classifications: </span>
<ol style="font-size: 10pt; font-family: Arial;">
<li><span style="font-family: Arial; font-size: small;"> Platinum (High quality) </span></li>
<li><span style="font-family: Arial; font-size: small;">Gold</span></li>
<li><span style="font-family: Arial; font-size: small;">Silver</span></li>
<li><span style="font-family: Arial; font-size: small;"> Bronze (Low quality) </span></li>
</ol>
<p><span style="font-family: Arial; font-size: small;"> The classification is based on the overall quality rating provided by our WsRF. Using WsRF values obtained for each Web services, we use a classification scheme to associate each Web services to a particular service group. The classification can be helpful to differentiate between various services that offer the same functionality. </span></p>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#C6C6AA"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="Download_0"></a>Download Instructions </span> </strong></td>
</tr>
<tr>
<td colspan="2"><span style="font-family: Arial; font-size: small;"> The QWS dataset is available free of charge for educational and non-commercial purposes. In exchange, we kindly request that you make available to us the results of running the QWS dataset. Please use the following references in citing the dataset: </span>
<ul>
<li><span style="font-family: Arial; font-size: small;"> Al-Masri, E., and Mahmoud, Q. H., "Discovering the best web service", (poster) 16th International Conference on World Wide Web (WWW), 2007, pp. 1257-1258. </span></li>
<li><span style="font-family: Arial; font-size: small;"> Al-Masri, E., and Mahmoud, Q. H., "QoS-based Discovery and Ranking of Web Services", IEEE 16th International Conference on Computer Communications and Networks (ICCCN), 2007, pp. 529-534. </span></li>
</ul>
<p><span style="font-family: Arial; font-size: small;"> Downloading and using the QWS Data will indicate your acceptance to enter into a <a href="http://www.gnu.org/copyleft/gpl.html"> GNU General Public License agreement </a>. Should the QWS Data be used in any scientific or educational study/research the authors will be accredited as the source of the data with any of the references listed above in citing the data. Redistribution of this data to any other third party or on the Web is not permitted. </span></p>
<p style="text-align: center;"><span style="font-family: Arial; font-size: small;"><span style="background-color: #ffff99;"> To get a copy of the QWS dataset, please click send an email to <strong><span style="color: #ff0000;">qwsdata[AT]yahoo.com</span></strong></span>. </span></p>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#C6C6AA"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="Applications_"></a>Applications </span> </strong></td>
</tr>
<tr>
<td colspan="2">
<ul>
<li><span style="font-family: Arial; font-size: small;"> Artificial Neural Network (ANN) for using the Service Classification as input to the network (identify high quality Web services) </span></li>
<li><span style="font-family: Arial; font-size: small;"> Web service status: determine using QWS dataset an overview of the existing status of Web services that exist on the Web today. </span></li>
</ul>
</td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#C6C6AA"><strong> <span style="font-size: 11pt; font-family: Arial;"> <a name="Contact_Us"></a>Contact Us </span> </strong></td>
</tr>
<tr>
<td colspan="2"><span style="font-family: Arial; font-size: small;"> Your comments and suggestions are welcome. Please send your comments by email: Eyhab Al-Masri (qwsdata[AT]yahoo.com) </span></td>
</tr>
<tr>
<td colspan="2">&nbsp;</td>
</tr>
<tr>
<td colspan="2" bgcolor="#808080">
<p align="center"><strong> <span style="font-family: Arial; font-size: xx-small;"> <span style="color: #ffffff;"> <br /> This page is maintained by Eyhab Al-Masri (</span><span style="color: #ffffff;">qwsdata[AT]yahoo.com</span><span style="color: #ffffff;"> ) Last modified November 2019.<br /> &nbsp; </span> </span> </strong></p>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
</div>
