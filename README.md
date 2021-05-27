# Roundcube-Plugin-Roundrive for NextCloud

This plugin is largely inspired by the plugin kolab_file
It can be used to connect on a WebDAV storage (like NextCloud) from Roundcube
You can add file from/to a mail on/from your storage

This plugin use the flysystem lib (https://github.com/thephpleague/flysystem)
It can be modify to use other storages like local storage, amazon, google, ...

License
-------

This plugin is released under the GNU Affero General Public License Version 3 (licence of kolab_file plugin)
(http://www.gnu.org/licenses/agpl-3.0.html).

Install
-------

* Place this plugin folder into plugins directory of Roundcube
* Add roundrive to $config['plugins'] in your Roundcube config

NB: When downloading the plugin from GitHub you will need to create a
directory called roundrive and place the files in there,
ignoring the root directory in the downloaded archive directory in the
downloaded archive. 
