CryptoLuck
=======
A simple Cryptocurrency-based lottery script.

Installation
------------
Set the configuration variables in config.inc.php.

Add a call in your crontab to run give_prize.php every day at the `$draw_time` time.

Create an address with the label "Lottery Pot" in your server wallet you are using for CryptoLuck.

Make sure the wallet has enough funds to cover transaction fees.

License
-------
This code is licensed under the [GNU Lesser General Public License v3.0](http://www.gnu.org/licenses/lgpl-3.0.txt).
