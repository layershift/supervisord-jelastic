Supervisor has been successfully installed.
To run supervisor instance, access your node via [SSH](http://kb.layershift.com/jelastic-ssh-access). Create an example config file with:

``cd ~/; echo_supervisord_conf > supervisord.conf``

Run your supervisor with

``supervisord -c /path/to/supervisord.conf``

Where **/path/to/supervisord.conf** is a full path to the configuration file you've just created.

More examples and detailed documentation can be found at [http://supervisord.org/](http://supervisord.org/).