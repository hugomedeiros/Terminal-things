# Terminal Things #

## SSH ##

### Para remover a Chave do SSH, troque hostname pelo ip do servidor e tudo ok. ###
<pre>ssh-keygen -R "hostname"</pre>

## Digital Ocean ##
###VESTA CP###

<pre>
ssh root@your.server
curl -O http://vestacp.com/pub/vst-install.sh
bash vst-install.sh
</pre>


# Development Things #

## Tools ##
### Compass ###
<pre>
gem update --system
gem install compass
</pre>

### grunt ###
<pre>
npm install -g grunt-cli
</pre>



## Grunt ##

### Install grunt modules ###
<pre>npm install</pre>

### Grunt commands ###
<pre>
grunt
grunt watch
grunt ftp
</pre>

### Gruntfile – Livereload ###
Adicione isso dentro de Watch

<pre>
livereload: {
	// Browser live reloading
	// https://github.com/gruntjs/grunt-contrib-watch#live-reloading
	options: {
		livereload: true
	},
	files: [
	'../assets/css/*.css',
	'../*.*'
	]
}
</pre>

