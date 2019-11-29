<html>
<head>
    <meta http-equiv="Content-Language" content="en-us">
    <meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
    <meta name="keywords" content="services, Web services, dataset, QWS, QoS, quality of service, quality, empirical, web service quality, web service, ranking, classification, neural networks">
    <title>The QWS Dataset</title>
</head>

<body bgcolor="#B9B9B9">
    <div align="center">
        <table border="1" width="800" cellspacing="0" cellpadding="5" id="table1" bordercolor="#808080" bgcolor="#FFFFFF">
            <tr>
                <td>
                    <table border="0" width="100%" cellspacing="0" cellpadding="0" id="table2">
                        <tr>
                            <td colspan="2">
                                <p align="center">
                                    <b>
                                        <font face="Verdana" size="5" color="#808080">
                                            The QWS Dataset
                                        </font>
                                    </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <div align="center">
                                    <table border="0" width="80%" cellspacing="0" cellpadding="0" bordercolor="#4684C1" id="table7">
                                        <tr>
                                            <td align="center">
                                                <font size="2" face="Verdana">
                                                    <a href="#About_">
                                                        About
                                                    </a>
                                                </font>
                                            </td>
                                            <td align="center">
                                                <font size="2" face="Verdana">
                                                    <a href="#Description_">Description</a>
                                                </font>
                                            </td>
                                            <td align="center">
                                                <font size="2" face="Verdana">
                                                    <a href="#Definitions">Definitions</a>
                                                </font>
                                            </td>
                                            <td align="center">
                                                <font size="2" face="Verdana">
                                                    <a href="#Download_0">Download</a>
                                                </font>
                                            </td>
                                            <td align="center">
                                                <font face="Verdana" size="2">
                                                    <a href="#Applications_">Applications</a>
                                                </font>
                                            </td>
                                            <td align="center">
                                                <font size="2" face="Verdana">
                                                    <a href="#Contact_Us">Contact</a>
                                                </font>
                                            </td>
                                        </tr>
                                    </table>
                                </div>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td colspan="2" bgcolor="#D6D6C0">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="About_">
                                            About
                                        </a> QWS Dataset
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <p align="justify">
                                    <font size="2" face="Arial">
                                        The main goal
                                        of this dataset is to offer a basis for Web Service researchers. To this end, this dataset contains 2507
                                        web services and their QoS measurements. The services were collected using my
                                    </font>
                                    <font size="2" face="Arial" color="#FFFFFF">
                                        <a href="http://www2007.org/poster968.php">Web Service Crawler Engine (WSCE)</a>.
                                    </font><font size="2" face="Arial">
                                        The majority of Web services were obtained from public sources on the Web including Universal Description,
                                        Discovery, and Integration (UDDI) registries, search engines, and service portals. The QWS Dataset includes
                                        a set of 2,507 Web services and their <a href="#Quality_of_Web_Service_(QWS)_">Quality of Web Service (QWS)</a>
                                        measurements that were conducted during the year of 2008 using our Web Service Broker (WSB) framework.
                                        Each row in this dataset represents a Web service and its corresponding nine QWS measurements (separated by commas).
                                        The first nine elements are QWS metrics that were measured using multiple Web service benchmark tools over a six-day period.
                                        The QWS values represent averages of the measurements collected during that period.
                                        The last two parameters represent the service name and reference to the WSDL document.
                                    </font>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#D6D6C0" colspan="2">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="Description_">Description</a> of QWS Dataset
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <font face="Arial" size="2">
                                    Each row in the
                                    dataset corresponds to an existing Web service
                                    implementation. The dataset contains a collection of web services from our service repository that were continuously monitored for particular service qualities
                                    including:
                                </font><p align="center">
                                    <b>
                                        <font face="Arial" size="2">QWS Parameters and Units</font>
                                    </b>
                                </p>
                                <div align="center">
                                    <table border="1" cellspacing="0" cellpadding="0" bordercolor="#C6C6AA" id="table8" width="95%">
                                        <tr>
                                            <td>
                                                <div align="center">
                                                    <table border="0" width="100%" id="table9" cellspacing="0" cellpadding="4">
                                                        <tr>
                                                            <td bgcolor="#5D7B9D" align="center" width="37">
                                                                <font face="Arial" size="2" color="#FFFFFF">ID</font>
                                                            </td>
                                                            <td bgcolor="#5D7B9D" align="center" width="153">
                                                                <font face="Arial" size="2" color="#FFFFFF">
                                                                    Parameter&nbsp; Name
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#5D7B9D" align="center">
                                                                <font face="Arial" size="2" color="#FFFFFF">
                                                                    Description
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#5D7B9D" align="center">
                                                                <font face="Arial" size="2" color="#FFFFFF">Units</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">1</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153"><font face="Arial" size="2">Response Time</font></td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Time taken to send a request and receive a response
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">ms</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">2</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153"><font face="Arial" size="2">Availability</font></td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    Number of successful invocations/total invocations
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">3</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153"><font face="Arial" size="2">Throughput</font></td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Total Number of invocations for a given period of
                                                                    time
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">invokes/second</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">4</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153"><font face="Arial" size="2">Successability</font></td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    Number of response / number of request messages
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">5</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153"><font face="Arial" size="2">Reliability</font></td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Ratio of the number of error messages to total
                                                                    messages
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">6</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153"><font face="Arial" size="2">Compliance</font></td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    The extent to which a WSDL document follows
                                                                    <a target="_blank" href="http://www.w3.org/TR/wsdl">WSDL specification</a>
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">7</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153"><font face="Arial" size="2">Best Practices</font></td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    The extent to which a Web service follows
                                                                    <a target="_blank" href="http://www.ws-i.org/Profiles/BasicProfile-2_0(WGD).html">WS-I Basic Profile</a>
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">8</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153"><font face="Arial" size="2">Latency</font></td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    Time taken for the server to process a given request
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">ms</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">9</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153">
                                                                <font face="Arial" size="2">
                                                                    <a href="#Documentation">Documentation</a>
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Measure of documentation (i.e. description tags) in
                                                                    WSDL
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">10</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153">
                                                                <font face="Arial" size="2">
                                                                    <a href="#Web_Service_Relevancy_Function_(WsRF)">WsRF</a>
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    Web Service Relevancy Function: a rank for Web
                                                                    Service Quality
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">%</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">11</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153">
                                                                <font face="Arial" size="2">
                                                                    <a href="#Service_Classification_">
                                                                        Service
                                                                        Classification
                                                                    </a>
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Levels representing service offering qualities (1
                                                                    through 4)
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">Classifier</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#FFFFFF" width="37" align="center">
                                                                <font size="2" face="Arial">12</font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" width="153"><font face="Arial" size="2">Service Name</font></td>
                                                            <td bgcolor="#FFFFFF">
                                                                <font face="Arial" size="2">
                                                                    Name of the Web service
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#FFFFFF" align="center">
                                                                <font face="Arial" size="2">None</font>
                                                            </td>
                                                        </tr>
                                                        <tr>
                                                            <td bgcolor="#F7F6F3" width="37" align="center">
                                                                <font size="2" face="Arial">13</font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" width="153"><font face="Arial" size="2">WSDL Address</font></td>
                                                            <td bgcolor="#F7F6F3">
                                                                <font face="Arial" size="2">
                                                                    Location of the Web Service Definition Language (WSDL)
                                                                    file on the Web
                                                                </font>
                                                            </td>
                                                            <td bgcolor="#F7F6F3" align="center">
                                                                <font face="Arial" size="2">None</font>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                </div>
                                            </td>
                                        </tr>
                                    </table>
                                </div>
                                <p>
                                    <font face="Arial" size="2">
                                        In order, the number associated with
                                        each property corresponds to a column within the QWS
                                        dataset.
                                    </font>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#D6D6C0" colspan="2">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="Definitions">Definitions</a>
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#E3E3D5">&nbsp;</td>
                            <td bgcolor="#E3E3D5" width="97%">
                                <p align="justify">
                                    <b>
                                        <font face="Arial" size="2" color="#0000FF">
                                            <a name="Documentation">Documentation</a>
                                        </font>
                                    </b>
                            </td>
                        </tr>
                        <tr>
                            <td width="99%" colspan="2">
                                <table border="0" width="100%" cellspacing="0" cellpadding="3" id="table6">
                                    <tr>
                                        <td width="21">&nbsp;</td>
                                        <td>
                                            <font face="Arial" size="2">
                                                One of the main
                                                properties of Web services is having proper
                                                documentation. The documentation QWS
                                                property provides a measure to the extent of which a
                                                Web service is self-describable and is based on
                                                examining WSDL documents including service name,
                                                description, operation name, description, message
                                                name, and message description tags.
                                            </font>
                                        </td>
                                    </tr>
                                </table>
                            </td>
                        </tr>
                        <tr>
                            <td bgcolor="#008000" colspan="2">
                                <img border="0" src="pixel.gif" width="1" height="1">
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#E3E3D5">&nbsp;</td>
                            <td bgcolor="#E3E3D5" width="97%">
                                <p align="justify">
                                    <font size="2" face="Arial" color="#0000FF">
                                        <b>
                                            <a name="Quality_of_Web_Service_(QWS)_">
                                                Quality of Web
                                                Service (QWS)
                                            </a>
                                        </b>
                                    </font>
                            </td>
                        </tr>
                        <tr>
                            <td width="99%" colspan="2">
                                <table border="0" width="100%" cellspacing="0" cellpadding="3" id="table3">
                                    <tr>
                                        <td width="21">&nbsp;</td>
                                        <td>
                                            <font size="2" face="Arial">
                                                Web service’s
                                                ability to provide selective treatment to various
                                                clients in the most effective
                                                manner.
                                            </font>
                                        </td>
                                    </tr>
                                </table>
                            </td>
                        </tr>
                        <tr>
                            <td bgcolor="#008000" colspan="2">
                                <img border="0" src="pixel.gif" width="1" height="1">
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#E3E3D5">&nbsp;</td>
                            <td bgcolor="#E3E3D5" width="97%">
                                <p align="justify">
                                    <b>
                                        <font face="Arial" size="2" color="#0000FF">
                                            <a name="Web_Service_Relevancy_Function_(WsRF)">
                                                Web Service
                                                Relevancy Function (WsRF)
                                            </a>
                                        </font>
                                    </b>
                            </td>
                        </tr>
                        <tr>
                            <td width="99%" colspan="2">
                                <table border="0" width="100%" cellspacing="0" cellpadding="3" id="table4">
                                    <tr>
                                        <td width="21">&nbsp;</td>
                                        <td>
                                            <font size="2" face="Arial">
                                                WsRF is used to
                                                measure the quality ranking of a Web service based
                                                on quality metrics (1 through 9 above).
                                            </font>
                                        </td>
                                    </tr>
                                </table>
                            </td>
                        </tr>
                        <tr>
                            <td bgcolor="#008000" colspan="2">
                                <img border="0" src="pixel.gif" width="1" height="1">
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#E3E3D5">&nbsp;</td>
                            <td bgcolor="#E3E3D5" width="97%">
                                <p align="justify">
                                    <b>
                                        <a name="Service_Classification_">
                                            <font face="Arial" size="2" color="#0000FF">
                                                Service
                                                Classification
                                            </font>
                                        </a>
                                    </b>
                            </td>
                        </tr>
                        <tr>
                            <td width="99%" colspan="2">
                                <table border="0" width="100%" cellspacing="0" cellpadding="3" id="table5">
                                    <tr>
                                        <td width="21">&nbsp;</td>
                                        <td>
                                            <font face="Arial" size="2">
                                                The service
                                                classification represents various levels of service
                                                offering qualities. There are four service
                                                classifications:
                                            </font><ol style="font-size: 10pt; font-family: Arial">
                                                <li>
                                                    <font face="Arial" size="2">
                                                        Platinum (High
                                                        quality)
                                                    </font>
                                                </li>
                                                <li><font face="Arial" size="2">Gold</font></li>
                                                <li><font face="Arial" size="2">Silver</font></li>
                                                <li>
                                                    <font face="Arial" size="2">
                                                        Bronze (Low
                                                        quality)
                                                    </font>
                                                </li>
                                            </ol>
                                            <p>
                                                <font face="Arial" size="2">
                                                    The classification is
                                                    based on the overall quality rating provided by our
                                                    WsRF. Using WsRF values obtained for each Web
                                                    services, we use a classification scheme to
                                                    associate each Web services to a particular service
                                                    group. The classification can be helpful to
                                                    differentiate between various services that offer
                                                    the same functionality.
                                                </font>
                                        </td>
                                    </tr>
                                </table>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#C6C6AA" colspan="2">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="Download_0">Download</a> Instructions
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <font face="Arial" size="2">
                                    The QWS dataset is available free of charge for educational and non-commercial purposes. In exchange, we kindly request that
                                    you make available to us the results of running the QWS
                                    dataset. Please use the following references in citing the dataset:
                                </font><ul>
                                    <li>
                                        <font face="Arial" size="2">
                                            Al-Masri, E., and
                                            Mahmoud, Q. H., &quot;Discovering the best web service&quot;, (poster) 16th
                                            International Conference on World Wide Web (WWW), 2007,
                                            pp. 1257-1258.
                                        </font>
                                    </li>
                                    <li>
                                        <font face="Arial" size="2">
                                            Al-Masri, E., and
                                            Mahmoud, Q. H., &quot;QoS-based Discovery and Ranking of Web
                                            Services&quot;, IEEE 16th International Conference on
                                            Computer Communications and Networks (ICCCN), 2007, pp.
                                            529-534.
                                        </font>
                                    </li>
                                </ul>
                                <p>
                                    <font size="2" face="Arial">
                                        Downloading and using the QWS
                                        Data will indicate your acceptance to enter into a
                                        <a href="http://www.gnu.org/copyleft/gpl.html">
                                            GNU General
                                            Public License agreement
                                        </a>. Should the QWS Data be used in
                                        any scientific or educational study/research the authors
                                        will be accredited as the source of the data with any of the
                                        references listed above in citing the data. Redistribution
                                        of this data to any other third party or on the Web is not
                                        permitted.
                                    </font>
                                </p>
                                <p>
                                    <font face="Arial" size="2">
                                        To get a copy of the QWS dataset, please click <a href="https://github.com/qwsdata/qwsdataset/blob/master/qwsdataset.txt">here</a>.
                                    </font>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#C6C6AA" colspan="2">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="Applications_">Applications</a>
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <ul>
                                    <li>
                                        <font face="Arial" size="2">
                                            Artificial Neural
                                            Network (ANN) for using the Service Classification as
                                            input to the network (identify high quality Web
                                            services)
                                        </font>
                                    </li>
                                    <li>
                                        <font face="Arial" size="2">
                                            Web service status:
                                            determine using QWS dataset an overview of the
                                            existing status of Web services that exist on the Web
                                            today.
                                        </font>
                                    </li>
                                </ul>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td bgcolor="#C6C6AA" colspan="2">
                                <b>
                                    <font face="Arial" style="font-size: 11pt">
                                        <a name="Contact_Us">Contact Us</a>
                                    </font>
                                </b>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">
                                <font face="Arial" size="2">
                                    Your comments and suggestions are welcome. Please send your comments by
                                    email: Eyhab Al-Masri (qwsdata[AT]yahoo.com)
                                </font>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2">&nbsp;</td>
                        </tr>
                        <tr>
                            <td colspan="2" bgcolor="#808080">
                                <p align="center">
                                    <b>
                                        <font face="Arial" size="1">
                                            <font color="#FFFFFF">
                                                <br>
                                                This page is maintained by Eyhab Al-Masri (</font><a href="mailto:qwsdata@yahoo.com"><font color="#FFFFFF">qwsdata[AT]yahoo.com</font></a><font color="#FFFFFF">
                                                )
                                                Last modified November 2019.<br>
                                                &nbsp;
                                            </font>
                                        </font>
                                    </b>
                            </td>
                        </tr>
                    </table>
                </td>
            </tr>
        </table>
    </div>

</body>

</html>

