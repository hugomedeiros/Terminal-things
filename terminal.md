# Terminal Things #

## SSH ##

### Para remover a Chave do SSH, troque hostname pelo ip do cervidor e tudo ok. ###
<pre>ssh-keygen -R "hostname"</pre>

##VESTA CP (Control Panel on Digital Ocean)##

### Connect to your server as root via SSH ###
<pre>ssh root@your.server</pre>

## Download installation script ###
<pre>curl -O http://vestacp.com/pub/vst-install.sh</pre>

## Run it ###
<pre>bash vst-install.sh</pre>


# Development Things #

## Tools ##
### Compass ###
<pre>
$ gem update --system
$ gem install compass
</pre>

## Grunt ##

### Livereload ###
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