# pihole-lists
#These lists will contain whitelists and blacklists of websites you might want to add to your pihole install
#
#
To use the 1-regex.txt or 1-whitelist.txt files you will need to create a cron job to move the contents 
to your regex file in your pihole directory, or you can just open up the file "/etc/pihole/regex.list" or "/etc/pihole/whitelist.list" 
in your favorite text editor or Webmin console and copy
the contents of my list into your list. Save and reboot your pihole. The same applies for the 1-blacklist.txt and 1-black.list files.
#
#
If you do not wish to go through the trouble of making and importing all the lists, I have compiled my favorite lists below that you can copy and paste into your pihole. Browse to your pihole admin page, and then go to Settings>Blocklists and paste all the URL's below into the available box. Click "Save and Update" and expect to wait around 15 minutes.

	https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts	
	http://sysctl.org/cameleon/hosts	
	https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt	
	https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt	
	https://github.com/ryanbr/fanboy-adblock/blob/master/popads-domains-list.txt	
	https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_all.list	
	https://raw.githubusercontent.com/mhxion/pornaway/master/hosts/porn_sites.txt	
	https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt	
	https://zerodot1.gitlab.io/CoinBlockerLists/hosts	
	https://github.com/d43m0nhLInt3r/socialblocklists/blob/master/TikTok/tiktokblocklist.txt	
	https://github.com/d43m0nhLInt3r/socialblocklists/blob/master/Snapchat/snapchatblocklist.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/porn0.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/porn1.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/porn2.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/porn3.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/porn4.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/ads1.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/ads2.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/cosmetic-surgery.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/costtraps.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/crypto-coinmining.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/dating.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/gambling.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/government.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/hacking-illegal.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/imagehosting.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/malware.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/modeling.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/proxies.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/searchengines_-_google-bing_allowed.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/sex-education.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/sex-lingerie.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/snapchat.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/spyware.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/tiktok.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/torrents.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/tracking.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/vpn.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/socialmedia.txt	
	# I usually keep this disabled    https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/news.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/1-whitelist.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/encrypted-DNS.txt	
	https://raw.githubusercontent.com/theycallmetimmy/pihole-lists/master/forums.txt
	https://raw.githubusercontent.com/oneoffdallas/dohservers/master/iplist.txt	
	https://www.github.developerdan.com/hosts/lists/dating-services-extended.txt	
	https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Adult	
	# this needs more work, it breaks a lot of stuff     https://dl.nrd-list.com/0/nrd-list-32-days.txt	
	# this needs more work, it breaks a lot of stuff     https://dl.threat-list.com/0/domains.txt	
	https://raw.githubusercontent.com/jumpsmm7/GeneratedAdblock/master/NoBypass.list
        https://v.firebog.net/hosts/AdguardDNS.txt
        https://urlhaus.abuse.ch/downloads/hostfile
        https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt
 	https://tools.wizworks.net/cnbl.txt
