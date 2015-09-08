# whitelist-blacklist-hashes
Blacklist or Whitelist hashes this supports OpenTracker

/* Blacklist file
 * to use in your server backend to block
 * Torrent Hashes
 *
 * Author @ Chris Owen
 * v 1.0.0
 *
 */

 /*
  * Just paste hashes here
  * Example
  * <hex></hex>
  * <hex></hex>
  *
  *
  * 183468309EC05C14AC9AB29DC4AF20055A73E3FD
  * 1F7821DF5179252FDC193B946B04786177B873D7
  *	208DD7F0B7B76ABECB351CAF674168345ABDF5B4
  *	23ECE83454AEA5A4E4F92AD2171C6CA9C94660FD
  *	2766FE1C4DC1BE84BCCF39B37BE3AC5955D499CC
  *
  *
  *	Open directory
  *
  *	$root :-> cd /etc
  *	$root :-> cd opentracker
  *	$root :-> nano blacklist.txt
  *
  *
  *	Now paste a new hash you want to block per line.
  *
  *	Start opentracker
  *
  *	./opentracker -b /etc/opentracker/blacklist.txt
  *
  *	by default it should run on port 6969
  *
  *	on both tcp : udp
  *
  *	unless you specify a new opentracker.conf file
  *
  *	sample can be seen in
  *
  *	opentracker.conf.sample
  *
  *
