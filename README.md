# addport

<li>Dedicated Port config generator for COLEGANET INSTALLER</li>
<li>Originally Created by cryptopool.builders for multipool installer</li>
<li>This generator will modify the main algo.conf file in stratum/config/</li>
<li>Edited to use custom port for Coleganet pool Installer</li>
<br>

<div><h2>Install</h2></div>
<code>cd /tmp</code><br>
<code>git clone https://github.com/Coleganet/addport.git</code><br>
<code>cd addport</code><br>
<code>sudo chmod +x addport</code><br>
<code>sudo cp -r addport /usr/bin/</code><br>

<div><h2>Usage</h2></div>
<p>run command in stratum server</p>
<code>addport</code>
<br><br>
<p>To START | RESTART | STOP STRATUM</p>
<code>stratum."coinsympol" start "coinsympol"</code><br>
<code>stratum."coinsympol" restart "coinsympol"</code><br>
<code>stratum."coinsympol" stop "coinsympol"</code><br>
<p>to view screen</p>
<code>screen -r "coinsympol"</code><br>
<br><br>
<p>example</p>
<p>"coinsympol" in lowercase</p>
<code>stratum.btc start btc</code>
