<h2>Apache Configuration Builder</h2>
![Apache Configuration Builder](https://raw.githubusercontent.com/ajwhite/Apache-Configuration-Builder/master/ApacheConfigurationBuilder.gif)


<h4>Instructions:</h4>
<p>This works best when it is placed in the root of your development folder that contains your project directories</p>
<ul>
	<li>Clone or copy the bash script into your workspace directory</li>
	<li>Call it with sudo -- sudo ./apacheBuilder.sh</li>
	<li>Fill out the prompts and your site will pop up as soon as you're done!</li>
</ul>


Notes: This is configured for Mac OS X environments with apache2 installed.<br/>
It is hard coded to use the following files:
<ul>
	<li>Hosts File: /etc/hosts</li>
	<li>VHosts File: /etc/apache2/extra/httpd-vhosts.conf</li>
</ul>

If your files exist in other places, make sure to edit the <strong>VHOST_FILE</strong> and <strong>HOST_FILE</strong>


