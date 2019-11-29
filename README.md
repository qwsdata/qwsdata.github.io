<div>
    <table bgcolor="#FFFFFF" border="1" cellpadding="5" cellspacing="0" width="800">
        <tbody>
            <tr>
                <td>
                    <table border="0" cellpadding="0" cellspacing="0" width="100%">
                        <tbody>
                            <tr>
                                <td colspan="2">
                                    <p style="text-align: center;"><strong>&nbsp;The QWS Dataset&nbsp;</strong></p>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2">
                                    <div style="text-align: center;">
                                        <table border="0" cellpadding="0" cellspacing="0" width="755">
                                            <tbody>
                                                <tr>
                                                    <td><a href="#About_">About</a></td>
                                                    <td><a href="#Description_">Description</a></td>
                                                    <td><a href="#Definitions">Definitions</a></td>
                                                    <td><a href="#Download_0">Download</a></td>
                                                    <td><a href="#Applications_">Applications</a></td>
                                                    <td><a href="#Contact_Us">Contact</a></td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#D6D6C0" colspan="2"><strong>&nbsp;<a name="About_"></a> About QWS Dataset&nbsp;</strong></td>
                            </tr>
                            <tr>
                                <td colspan="2">
                                    <p style="text-align: justify;">The main goal of this dataset is to offer a basis for Web Service researchers. To this end, this dataset contains 2507 web services and their QoS measurements. The services were collected using my <a href="http://www2007.org/poster968.php">Web Service Crawler Engine (WSCE)</a>.
                                        The majority of Web services were obtained from public sources on the Web including Universal Description, Discovery, and Integration (UDDI) registries, search engines, and service portals. The QWS Dataset includes
                                        a set of 2,507 Web services and their <a href="#Quality_of_Web_Service_(QWS)_">Quality of Web Service (QWS)</a> measurements that were conducted during the year of 2008 using our Web Service Broker (WSB) framework.
                                        Each row in this dataset represents a Web service and its corresponding nine QWS measurements (separated by commas). The first nine elements are QWS metrics that were measured using multiple Web service benchmark
                                        tools over a six-day period. The QWS values represent averages of the measurements collected during that period. The last two parameters represent the service name and reference to the WSDL document.</p>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#D6D6C0" colspan="2">
                                    <div style="text-align: justify;"><strong>&nbsp;<a name="Description_"></a>Description of QWS Dataset&nbsp;</strong></div>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2">Each row in the dataset corresponds to an existing Web service implementation. The dataset contains a collection of web services from our service repository that were continuously monitored for particular service qualities
                                    including:
                                    <p><strong>&nbsp;QWS Parameters and Units&nbsp;</strong></p>
                                    <div>
                                        <table border="1" cellpadding="0" cellspacing="0" width="95%">
                                            <tbody>
                                                <tr>
                                                    <td>
                                                        <div>
                                                            <table border="0" cellpadding="4" cellspacing="0" width="100%">
                                                                <tbody>
                                                                    <tr>
                                                                        <td bgcolor="#5D7B9D" style="width: 5.02717%;">ID</td>
                                                                        <td bgcolor="#5D7B9D" style="width: 25.8152%;">Parameter Name</td>
                                                                        <td bgcolor="#5D7B9D" style="width: 48.913%;">Description</td>
                                                                        <td bgcolor="#5D7B9D" style="width: 14.8098%;">Units</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">1</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;">Response Time</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Time taken to send a request and receive a response</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">ms</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">2</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;">Availability</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">Number of successful invocations/total invocations</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">3</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;">Throughput</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Total Number of invocations for a given period of time</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">invokes/second</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">4</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;">Successability</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">Number of response / number of request messages</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">5</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;">Reliability</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Ratio of the number of error messages to total messages</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">6</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;">Compliance</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">The extent to which a WSDL document follows <a href="http://www.w3.org/TR/wsdl" rel="noopener" target="_blank">WSDL specification</a></td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">7</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;">Best Practices</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">The extent to which a Web service follows <a href="http://www.ws-i.org/Profiles/BasicProfile-2_0(WGD).html" rel="noopener" target="_blank">WS-I Basic Profile</a></td>
                                                                        <td bgcolor="#F7F6F3"
                                                                            style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">8</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;">Latency</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">Time taken for the server to process a given request</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">ms</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">9</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;"><a href="#Documentation">Documentation</a></td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Measure of documentation (i.e. description tags) in WSDL</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">10</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;"><a href="#Web_Service_Relevancy_Function_(WsRF)">WsRF</a></td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">Web Service Relevancy Function: a rank for Web Service Quality</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">%</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">11</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;"><a href="#Service_Classification_">Service Classification</a></td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Levels representing service offering qualities (1 through 4)</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">Classifier</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#FFFFFF" style="width: 5.02717%;">12</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 25.8152%;">Service Name</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 48.913%;">Name of the Web service</td>
                                                                        <td bgcolor="#FFFFFF" style="width: 14.8098%;">None</td>
                                                                    </tr>
                                                                    <tr>
                                                                        <td bgcolor="#F7F6F3" style="width: 5.02717%;">13</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 25.8152%;">WSDL Address</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 48.913%;">Location of the Web Service Definition Language (WSDL) file on the Web</td>
                                                                        <td bgcolor="#F7F6F3" style="width: 14.8098%;">None</td>
                                                                    </tr>
                                                                </tbody>
                                                            </table>
                                                        </div>
                                                    </td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div>
                                    <p>In order, the number associated with each property corresponds to a column within the QWS dataset.</p>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#D6D6C0" colspan="2"><strong>&nbsp;<a name="Definitions"></a>Definitions&nbsp;</strong></td>
                            </tr>
                            <tr>
                                <td bgcolor="#E3E3D5" width="97%">
                                    <p><strong>&nbsp;<a name="Documentation"></a>Documentation&nbsp;</strong></p>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2" width="99%">
                                    <table border="0" cellpadding="3" cellspacing="0" width="100%">
                                        <tbody>
                                            <tr>
                                                <td>One of the main properties of Web services is having proper documentation. The documentation QWS property provides a measure to the extent of which a Web service is self-describable and is based on examining
                                                    WSDL documents including service name, description, operation name, description, message name, and message description tags.</td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#E3E3D5" width="97%">
                                    <p><strong>&nbsp;<a name="Quality_of_Web_Service_(QWS)_"></a> Quality of Web Service (QWS)&nbsp;</strong></p>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2" width="99%">
                                    <table border="0" cellpadding="3" cellspacing="0" width="100%">
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
                                    <p><strong>&nbsp;<a name="Web_Service_Relevancy_Function_(WsRF)"></a> Web Service Relevancy Function (WsRF)&nbsp;</strong></p>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2" width="99%">
                                    <table border="0" cellpadding="3" cellspacing="0" width="100%">
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
                                    <p><strong>&nbsp;<a name="Service_Classification_"></a> Service Classification&nbsp;</strong></p>
                                </td>
                            </tr>
                            <tr>
                                <td colspan="2" width="99%">
                                    <table border="0" cellpadding="3" cellspacing="0" width="100%">
                                        <tbody>
                                            <tr>
                                                <td>The service classification represents various levels of service offering qualities. There are four service classifications:
                                                    <ol>
                                                        <li>Platinum (High quality)</li>
                                                        <li>Gold</li>
                                                        <li>Silver</li>
                                                        <li>Bronze (Low quality)</li>
                                                    </ol>
                                                    <p>The classification is based on the overall quality rating provided by our WsRF. Using WsRF values obtained for each Web services, we use a classification scheme to associate each Web services to a particular
                                                        service group. The classification can be helpful to differentiate between various services that offer the same functionality.</p>
                                                </td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#C6C6AA" colspan="2"><strong>&nbsp;<a name="Download_0"></a>Download Instructions&nbsp;</strong></td>
                            </tr>
                            <tr>
                                <td colspan="2">The QWS dataset is available free of charge for educational and non-commercial purposes. In exchange, we kindly request that you make available to us the results of running the QWS dataset. Please use the following references
                                    in citing the dataset:
                                    <ul>
                                        <li>Al-Masri, E., and Mahmoud Q. H., &quot;Investigating web services on the world wide web&quot;, 17th international conference on World Wide Web (WWW &#39;08), ACM, pp.795-804.</li>
                                        <li>Al-Masri, E., and Mahmoud, Q. H., &quot;Discovering the best web service&quot;, (poster) 16th International Conference on World Wide Web (WWW), 2007, pp. 1257-1258.</li>
                                        <li>Al-Masri, E., and Mahmoud, Q. H., &quot;QoS-based Discovery and Ranking of Web Services&quot;, IEEE 16th International Conference on Computer Communications and Networks (ICCCN), 2007, pp. 529-534.</li>
                                    </ul>
                                    <p>Downloading and using the QWS Data will indicate your acceptance to enter into a <a href="http://www.gnu.org/copyleft/gpl.html">&nbsp;GNU General Public License agreement&nbsp;</a>. Should the QWS Data be used in any
                                        scientific or educational study/research the authors will be accredited as the source of the data with any of the references listed above in citing the data. Redistribution of this data to any other third party
                                        or on the Web is not permitted.</p>
                                    <p style="text-align: center;"><span style="font-size: 18px;"><span style="color: rgb(184, 49, 47);">To get a copy of the QWS dataset, please click send an email to&nbsp;</span><strong><span style="color: rgb(184, 49, 47);">qwsdata[AT]yahoo.com</span></strong></span>
                                    </p>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#C6C6AA" colspan="2"><span style="font-size: 18px;"><strong>&nbsp;<a name="Applications_"></a>Applications&nbsp;</strong></span></td>
                            </tr>
                            <tr>
                                <td colspan="2">
                                    <ul>
                                        <li><span style="font-size: 18px;">Web Service Classification</span></li>
                                        <li><span style="font-size: 18px;">Web Service Composition</span></li>
                                        <li><span style="font-size: 18px;">Web Service QoS Performance&nbsp;</span></li>
                                        <li><span style="font-size: 18px;">Web Service QoS Prediction</span></li>
                                        <li><span style="font-size: 18px;">Web Service Ranking</span></li>
                                        <li><span style="font-size: 18px;">Web services Discovery</span></li>
                                        <li><span style="font-size: 18px;">Web services Modeling</span></li>
                                        <li><span style="font-size: 18px;">Web Services&#39; Resource Management</span></li>
                                        <li><span style="font-size: 18px;">Web Service Coordination</span></li>
                                        <li><span style="font-size: 18px;">Service Orientated Analysis</span></li>
                                        <li><span style="font-size: 18px;">Web Service Transaction</span></li>
                                        <li><span style="font-size: 18px;">Business process Integration and Management</span></li>
                                        <li><span style="font-size: 18px;">Web Service Recommender System</span><br><br></li>
                                    </ul>
                                </td>
                            </tr>
                            <tr>
                                <td bgcolor="#C6C6AA" colspan="2"><span style="font-size: 18px;"><strong>&nbsp;<a name="Contact_Us"></a>Contact Us&nbsp;</strong></span></td>
                            </tr>
                            <tr>
                                <td colspan="2">
                                    <div style="text-align: center;"><span style="font-size: 18px;">Your comments and suggestions are welcome.<br>Please send your comments by email: Eyhab Al-Masri (qwsdata[AT]yahoo.com)</span></div>
                                    <div style="text-align: center;"><span style="font-size: 18px;"><em>Last modified November 2019</em></span></div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
        </tbody>
    </table>
</div>
<p><span style="font-size: 18px;"><br></span></p>

<meta name="google-site-verification" content="FSbcqRZ737uLIaugzPbAVGP6JdCPY_Q4U2DvaNnn4wI" />
