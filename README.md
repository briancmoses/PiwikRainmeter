PiwikRainmeter
==============

This is a RainMeter skin which queries the Piwik Reporting API and parses returned XML and displays that information within the skin for the configured Piwik site.

Credit
======
Thanks to [poiru][poiru] whose theme/skins I based this new skin off of.

### Installation Instructions ###

1. Gather the necessary data for the [Piwik API][piwikapi]
	a. Piwik URL
	a. Your Piwik Site ID
	a. Your Piwik authentication token
1. Download and install [Rainmeter][rainmeter] 
1. Download and install my [Rainmeter Piwik Skin][piwikskin_da] from [DeviantArt][piwikskin_da], [GitHub][piwikskin_gh] or from [my blog][piwikskin_bm]
1. Locate the downloaded file (_Piwik_1.0.0.rmskin_), double-click it and click Install.
1. Right-click the Rainmeter icon in the system tray, or right-click an existing skin on your desktop and navigate to Rainmeter>Manage
1. Click Edit and modify the following found under  [Variables] to match your own Piwik information from Step 1

        SiteURL="Demo.Piwik.Org"
        PiwikURL="http://demo.piwik.org"
        PiwikSiteID=7
        PiwikAuthToken="anonymous"
1. Expand the Piwik folder and sub folder, select _Piwik.ini_ and click Load

[piwikapi]:http://developer.piwik.org/api-reference/reporting-api "Piwik Reporting API Reference"
[piwikskin_da]:http://briancmoses.deviantart.com/art/Piwik-1-0-0-498845640  "Piwik Skin for Rainmeter on DeviantArt"
[piwikskin_gh]:https://github.com/briancmoses/PiwikRainmeter "Piwik Skin for Rainmeter on GitHub"
[piwikskin_bm]:/Downloads/PiwikRainmeter/Piwik_1.0.0.rmskin "Piwik Skin for Rainmeter from BrianMoses.net"
[piwik]:http://piwik.org "Piwik"
[rainmeter]:http://rainmeter.net/ "Rainmeter"
[poiru]:http://poiru.deviantart.com "Poiru's DeviantART Page"
