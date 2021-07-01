# SQL-Injection-Detection
<p>SQL Injection continues to be one of the most damaging security exploits in terms of personal<br>
information exposure as well as monetary loss. Injection attacks are the number one vulnerability in the<br>
most recent OWASP Top 10 report, and the number of these attacks continues to increase. Traditional<br>
defense strategies often involve static, signature-based IDS (Intrusion Detection System) rules which are<br>
mostly effective only against previously observed attacks but not unknown, or zero-day, attacks. Much<br>
current research involves the use of machine learning techniques, which are able to detect unknown<br>
attacks, but depending on the algorithm can be costly in terms of performance. In addition, most current<br>
intrusion detection strategies involve collection of traffic coming into the web application either from a<br>
network device or from the web application host, while other strategies collect data from the database<br>
server logs. In this project, we are collecting traffic from two points: the web application host, and a<br>
Datiphy appliance node located between the webapp host and the associated MySQL database server. In<br>
our analysis of these two datasets, and another dataset that is correlated between the two, we have been<br>
able to demonstrate that accuracy obtained with the correlated dataset using algorithms such as rulebased and <br>
decision tree are nearly the same as those with a neural network algorithm, but with greatly<br>
improved performance.</p>
