#EXTM3U billed-msg="INTEK IPTV"
#EXTM3U x-tvg-url="https://www.dens.tv/sitemap.xml,https://raw.githubusercontent.com/azimabid00/epg/main/unifi_epg.xml,https://raw.githubusercontent.com/AqFad2811/epg/main/rtmklik.xml,https://raw.githubusercontent.com/AqFad2811/epg/main/singapore.xml,https://raw.githubusercontent.com/AqFad2811/epg/main/indonesia.xml,https://raw.githubusercontent.com/mitthu786/tvepg/main/tataplay/epg.xml.gz"

#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/en/thumb/f/f4/Logo_of_TV1_%28Malaysia%29.svg/656px-Logo_of_TV1_%28Malaysia%29.svg.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",TV1
https://d25tgymtnqzu8s.cloudfront.net/smil:tv1/playlist.m3u8?id=1

#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/TV2_RTM.png/220px-TV2_RTM.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",TV2
https://d25tgymtnqzu8s.cloudfront.net/smil:tv2/playlist.m3u8?id=2

#EXTINF:-1 tvg-logo="https://linear-poster.astro.com.my/prod/logo/TV3_v1.png" group-logo="httpss://astrogo.astro.com.my/staticFiles/images/icons/astroLogo.png" group-title="🎥",TV3 
#KODIPROP:inputstream=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=3bc3f0e518aed92e80a98118e5bc2c10:5fce364fbc4499856597b19a96f44648
https://get.perfecttv.net/dash2.mpd?username=vip_0new9imx&password=Wm75SsLs&channel=tv3

#EXTINF:-1 tvg-id="RTB Sukmaindera" ch-number="" tvg-name="AWESOME TV" group-title="🎥" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/1/1d/Awesome_TV_Malaysia.png", AWESOME TV
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=60f202b16407fedd8e369c32af57dd10:c8475231c09dc1b639886976b6fc7575
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2708.ts

#EXTINF:-1 group-logo="https://is.gd/prima.png" group-title="🎥" tvg-id="105.astro" tvg-logo="https://get.perfecttv.net/logo/primafhd.png" ,118 Prima FHD
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=6613bc303647468c974c3c839d5201e9:5422811c83996a25f51229219b41c410
#https://get.perfecttv.net/1080.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=primafhd|authorization=Bearer 
https://get.perfecttv.net/jwt.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=primafhd|user-agent=Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/113.0

#EXTINF:-1 tvg-id="okey" ch-number="" tvg-name="Enjoy TV5" group-title="MALAYSIA" tvg-logo="https://get.perfecttv.net/logo/enjoytv5.png", 109 Enjoy TV5
https://get.perfecttv.net/mytv.m3u8?channel=tv5


#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/jomngaji.png" ,124 Jom Ngaji
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0
https://df14pcdp16s98.cloudfront.net/v1/dash/951fbca46ac9b52422f8e3d6d4d6dab33623c3cc/FASTOO_CH6_JOMNGAJI/dash.mpd?username=vip_3klp0es8&password=wg3piwEs&aws.sessionId=10062fbd-3f7d-49e1-8f2b-95cd04543d7d

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/lawaksentral.png" ,125 Lawak Sentral
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0
https://1938ecee77d844ba8727487421f36e44.mediatailor.ap-southeast-1.amazonaws.com/v1/dash/951fbca46ac9b52422f8e3d6d4d6dab33623c3cc/FASTOO_CH3_LAWAK/dash.mpd?username=vip_3klp0es8&password=wg3piwEs&aws.sessionId=440ab476-481d-4d09-b7b0-3664e8652ede

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/ohmyceria.png" ,126 Oh My Ceria
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0
https://df14pcdp16s98.cloudfront.net/v1/dash/951fbca46ac9b52422f8e3d6d4d6dab33623c3cc/FASTOO_CH7_CERIA/dash.mpd?aws.sessionId=653a17be-4813-4757-8724-ae68ab7a34b7

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/dramahebat.png" ,127 Drama Hebat
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0
https://df14pcdp16s98.cloudfront.net/v1/dash/951fbca46ac9b52422f8e3d6d4d6dab33623c3cc/FASTOO_CH1_DRAMAHEBAT/dash.mpd?username=vip_3klp0es8&password=wg3piwEs&aws.sessionId=449fab5e-19fb-4843-9cc5-8209e03a725d

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/filemmantap.png" ,128 Filem Mantap
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0
https://df14pcdp16s98.cloudfront.net/v1/dash/951fbca46ac9b52422f8e3d6d4d6dab33623c3cc/FASTOO_CH2_FILEMMANTAP/dash.mpd?username=vip_3klp0es8&password=wg3piwEs&aws.sessionId=273a091c-2f5b-4571-bf71-269dbd89263e





#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/b/b9/Okey_RTM.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",TVokey
https://d25tgymtnqzu8s.cloudfront.net/smil:okey/playlist.m3u8?id=3


#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/TV6_Logo.jpg/800px-TV6_Logo.jpg" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",TV6
https://d25tgymtnqzu8s.cloudfront.net/smil:tv6/playlist.m3u8?id=6

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/tv7my.png" group-title="🎥",NTV7
https://mifntechnology.github.io/siaranMy/channels/DidikTvKPM/index.m3u8



#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"BW4eSVc9LK7ly0/nj4xPPQ", "kid":"qcYZB07TjCDiWtNsPFfBDA" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="108.unifi" tvg-logo="https://playtv.unifi.com.my:7220/CPS/images/universal/film/logo/201907/20190708/20190708074041526yld.png" group-logo="" group-title="🎥",8TVᵘⁿⁱᶠⁱ 
https://unifi-live07.secureswiftcontent.com/UnifiHD/live08.mpd


#EXTINF:-1 tvg-id= tvg-logo="https://playtv.unifi.com.my:7220/CPS/images/universal/film/logo/202202/20220217/20220217003547137q8t.png" group-logo="" group-title="🎥",TV9ᵘⁿⁱᶠⁱ 
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"Zfavh1DSSyMNkbmEI3rB5A", "kid":"HfqKZFr0HoPFIL3fkTk0yg" } ], "type":"temporary" }
https://unifi-live09.secureswiftcontent.com/UnifiHD/live09.mpd

#EXTINF:-1 tvg-id="tvs" ch-number="122" tvg-name="TVS" group-title="🎥" tvg-logo="https://get.perfecttv.net/logo/tvs.png",107 TVS
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=c3e956b38ae993be1494c7cfa17b1110:55ccaee886b340dd901f4bf8dd9d3a6a
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
https://get.perfecttv.net/astro_10802.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=tvs


#EXTINF:-1 group-title="🎥" tvg-id="TVAlhijrah" tvg-name="TvAlhijrah" tvg-logo="https://github.com/MIFNtechnology/siaranMy/raw/main/logo/TvAlhijrah.png", Tv Alhijrah
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key={"4745ac4464797aa9d5ed653c1e987917": "ffe2dd898757fb14c156b3e014058ecc"}
https://unifi-live01.secureswiftcontent.com/UnifiHD/live07.mpd

#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/RTM_Asean_%282024%29.svg/250px-RTM_Asean_%282024%29.svg.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",ASEAN
https://d25tgymtnqzu8s.cloudfront.net/event/smil:event1/chunklist_b2596000_slENG.m3u8

#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Logo_Berita_RTM.png/800px-Logo_Berita_RTM.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",berita
https://d25tgymtnqzu8s.cloudfront.net/smil:berita/playlist.m3u8?id=5

#EXTINF:-1 tvg-name="" tvg-id="AstroAwani.my" tvg-logo="https://i.ibb.co.com/L5xTZgk/asawani.png" group-title="🎥",AWANI 
https://d2idp3hzkhjpih.cloudfront.net/out/v1/4b85d9c2bf97413eb0c9fd875599b837/index.m3u8

#EXTINF:-1 group-title="🎥" tvg-id="BernamaTV" tvg-name="BernamaTV" tvg-logo="https://github.com/MIFNtechnology/siaranMy/raw/main/logo/Bernama.png", BERNAMA
https://mifntechnology.github.io/siaranMy/channels/Bernama/index.m3u8

#EXTINF:-1 group-title="🎥" tvg-id="Channel 5" tvg-chno="Channel 5" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/main/ch5sing.png",Channel 5
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=1b8ee3db17d34547983a2c3ddc3d28fc:fb5deb5f688fd67ec20c71191c7f4590
https://tglmp02.akamaized.net/out/v1/8c503a6966554d439035588f10505eee/manifest.mpd


#EXTINF:-1 group-title="🎥" tvg-id="Suria" tvg-chno="Suria" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/main/suria.png",Suria
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=db646b3742ba42718a28436a1f401aa8:75a545066954b9b7fafa96d72a844e00
https://tglmp04.akamaized.net/out/v1/00ac947de8174a54bd0f52226115d1db/manifest.mpd

#KODIPROP:inputstreamaddon=inputstream.adaptive 
#KODIPROP:inputstream.adaptive.manifest_type=dash 
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"MbNI0FlZPIH463qPX5madg", "kid":"/NsMITaNTGqo9MCOTNRCVg" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="Vasantham" tvg-logo="https://poster.starhubgo.com/Linear_channels2/105_1920x1080_HTV.png" group-logo="" group-title="🎥",Vasantham 
https://rest-as.ott.kaltura.com/api_v3/service/assetFile/action/playManifest/partnerId/147/assetId/237653/assetType/media/assetFileId/13229990/contextType/PLAYBACK/isAltUrl/False/a.mpd


#EXTINF:-1 tvg-name="" tvg-id="Channel NewsAsia HD" tvg-logo="https://i.ibb.co.com/RCS6JWF/cna.png" group-title="🎥",CNA 🇸🇬 
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=7cb90b341f444e4ca3fb60de2ed3d6e5:5640220b78729773fbeaabc19a502b50
https://d2e1asnsl7br7b.cloudfront.net/7782e205e72f43aeb4a48ec97f66ebbe/index.m3u8

#EXTINF:-1 tvg-name="" tvg-id="Channel NewsAsia HD" tvg-logo="https://i.imgur.com/VvEz0XX.png" group-title="🎥",just for laugh
https://service-stitcher.clusters.pluto.tv/v1/stitch/embed/hls/channel/6093f48c95132a00075fd859/master.m3u8?deviceId=channel&deviceModel=web&deviceVersion=1.0&appVersion=1.0&deviceType=rokuChannel&deviceMake=rokuChannel&deviceDNT=1&advertisingId=channel&embedPartner=rokuChannel&appName=rokuchannel&is_lat=1&bmodel=bm1&content=channel&platform=web&tags=ROKU_CONTENT_TAGS&coppa=false&content_type=livefeed&rdid=channel&genre=ROKU_ADS_CONTENT_GENRE&content_rating=ROKU_ADS_CONTENT_RATING&studio_id=viacom&channel_id=channel

#EXTINF:-1 tvg-id="AlJaz" tvg-name="AlJazeera" tvg-logo="https://gitee.com/suxuang/TVlogo/raw/main/img/AlJazeera.png" group-title="🎥",Al Jazeera
http://live-hls-web-aje.getaj.net/AJE/01.m3u8

#EXTINF:-1 tvg-id="AlJaz" tvg-name="AlJazeera" tvg-logo="https://upload.wikimedia.org/wikipedia/he/thumb/1/17/Reshet13Logo2022.svg/559px-Reshet13Logo2022.svg.png" group-title="🎥", kan 13
https://d2xg1g9o5vns8m.cloudfront.net/out/v1/0855d703f7d5436fae6a9c7ce8ca5075/index.m3u8

#EXTINF:-1 tvg-id="AlJaz" tvg-name="AlJazeera" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/KanHinuchit.svg/640px-KanHinuchit.svg.png" group-title="🎥", kan23
https://kan23.media.kan.org.il/hls/live/2024691/2024691/master.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/nhkworld.png" group-title="🎥",NHK World Japan
https://master.nhkworld.jp/nhkworld-tv/playlist/live.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/bs.png" group-title="🎥",Berita Satu
https://beritasatu.secureswiftcontent.com/han/beritasatu/bsatu10008/srtoutput/manifest.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/cnnindo.png" group-title="🎥",CNN Indonesia HD
https://live.cnnindonesia.com/livecnn/smil:cnntv.smil/chunklist_w2099542994_b384000_sleng.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/cnbcindo.png" group-title="🎥",CNBC Indonesia
https://live.cnbcindonesia.com/livecnbc/smil:cnbctv.smil/chunklist.m3u8

#EXTINF:-1 tvg-id="Animax.MACAN" tvg-name="Animax" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/horre.png" group-title="🎥",HORRE
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=0a3aaee779e940db8ff24f9f3eb5c98a:440e1c1ce9ba337844409c8bcad5a268
https://atemecdnbalancer-voe.sysln.id/live/eds/HoreeHD/mpd/HoreeHD.mpd



#=====kids=========

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="611.astro" tvg-logo="https://get.perfecttv.net/logo/ceria2.png" group-logo="" ,205 Ceria
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=b6e60ca0d28e8f97395f07b4e2e53a10:0f0ea6c3543c29d7f513eb886eb74f88
https://get.perfecttv.net/1080ceria.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=ceria|User-Agent=Mozilla/5.0 (Linux; Android 14; SMRV076G Build/UKQ1.240805.002; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/134.0.6950.85 Mobile Safari/537.366
			
#EXTINF:-1 player-buffer="6" group-logo="" group-title="🎥" tvg-id="555.unifi" ch-number="555" tvg-logo="https://get.perfecttv.net/logo/cartoonito.png" group-logo="", 206 Cartoonito
#KODIPROP:inputstream.adaptive.license_type=com.widevine.alpha
#KODIPROP:inputstream.adaptive.license_key=https://ottweb.hypp.tv:8064/?deviceId=YWJlZmRiODAtNmMwZS0zOGEzLWJmYzAtMzY4MDRiOTFhNWU1
https://web.hypp.tv:443/PLTV/88888888/224/3221227534/3221227534.mpd?rrsip=web.hypp.tv:443&zoneoffset=0&servicetype=1&icpid=&accounttype=1&limitflux=-1&limitdur=-1&accountinfo=tnUM3pus6bSh1mr%2FQqP7gS%2BLhDQRCdSHNpB7NvbJKHORk%2F7o9ZSvEMcHdX5yljqg9BPtBbwcQhknqc39VUJpD%2FHl2ogHz3eAyG2k7xToFQmJBU24%2BKwsNeA0VE3pRwoj%3A20221124094239%3AUTC%2C1001767137%2C115.164.56.153%2C20221124094239%2Curn:Huawei:liveTV:SP0010059884%2C1001767137%2C-1%2C0%2C1%2C%2C%2C2%2C595%2C%2C%2C2%2C1612403%2C0%2C517698%2C2706399750%2C%2C%2C2%2C1%2CEND&GuardEncType=2&it=H4sIAAAAAAAAADWOUQuCMBzEv80exzaHtoc9FUEQFmS9xt_5d4nT1aZC3z4tezq4u99xQwCDh50uJcs4T6DeGClnUSZLZFIyxoSCjEsS8ZV7LYgB55re5r5asNtle-eMMioEp1yQYpnbO7BrMx-7EoNO_tgFw9QY1FWs6QSRgrUBLQyN7-nZwfsa3FohWKzXeJoqoVjGUqUkGRa3gNjOCXlA3PruCQGro7dfQNfgIpInmBYs5tCh7kfnftwpVPObD9dw2Of0AAAA&tenantId=6001

#EXTINF:-1 tvg-id="551.unifi" tvg-name"Moonbug Kids" group-title="🎥" tvg-logo="https://get.perfecttv.net/logo/moonbug.png" ,207 Moonbug
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=e3cb7499710786eb105fab7b52459910:8ab093adabdc343b8734b7ecf0aea11a
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=moonbug

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="616.astro" tvg-logo="https://get.perfecttv.net/logo/nickelodeon.png" group-logo="" , 208 Nickelodeon
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=d8520e96a1283ab6e5be538474bfa810:bda5f7bbc1e44096f779a0619fe9881f
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Linux; Android 12; Pixel 3a XL Build/SP2A.220505.008; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/114.0.5715.0 Mobile Safari/537.36
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=nickelodeon

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="617.astro" tvg-logo="https://get.perfecttv.net/logo/nickjr.png" group-logo="", 209 Nick Junior
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=fa65220c9f76e424173899df533a6d10:b4abbee95b69b3e80a0d141272c870db
http://linearjitp-playback.astro.com.my/dash-wv/linear/9982/default_ott.mpd


#EXTINF:-1 tvg-id="CartoonNetwork" tvg-name="" group-title="🎥" tvg-logo="https://get.perfecttv.net/logo/cn.png" group-logo="",211 Cartoon Network
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=1a05bebf706408431a390c3f9f40f410:89c5ff9f8e65c7fe966afbd2f9128e5f
http://linearjitp-playback.astro.com.my/dash-wv/linear/509/default_ott.mpd

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="620.astro" tvg-logo="https://get.perfecttv.net/logo/cbeebies.png", 212 CBeebies   
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=50c699c444e5f80dacafc4c99667d810:de6c5feaae5f6963b4b392ddc8b6a778
http://linearjitp-playback.astro.com.my/dash-wv/linear/5093/default_ott.mpd

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="620.astro" tvg-logo="https://get.perfecttv.net/logo/blippi.png", 213 Blippi and Friends   
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=b1119e01b67a19a3eb37c41140c3fa10:5124996ebcfee077b4aacec307f38d0f
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
https://linearjitp-playback.astro.com.my/dash-wv/linear/5175/default_ott.mpd

EXTINF:-1  tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/kidstv.png" group-title="🎥",KIDS TV
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=17340c4223a4674b1b7da8d8d9e11174:11a73aad2c75ddf338840b08fb915993
https://legacy-global-cdn.visionplus.id/live/eds/Kids-HD/sa_dash/Kids-HD.mpd

#EXTINF:-1 tvg-id="" tvg-country="" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/mykids.png" group-title="🎥",my Kids
#EXTVLCOPT:http-referrer=https://www.dens.tv/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0
http://op-group1-swiftservesd-1.dens.tv/h/h191/index.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/zoomoo.png" group-title="🎥",ZOO MOO ASIA
https://zoomoo-samsungau.amagi.tv/playlist.m3u8
#EXTINF:-1 tvg-id="Boomerang.MACAN" tvg-name="Boomerang" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/cn.png" group-title="🎥",Cartoon Network
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=12fee297311f4bab91367d0e9c3a0a2f:656071dbdffbda440a6fde4fda56de21
https://atemeshield1-voe.sysln.id/live/eds/CartoonNetWHD/mpd/CartoonNetWHD.mpd

#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=f2c313fce55344e5a52389741d1f53f8:bae1e47db562b66895beb8fccdf2ad8a
#EXTINF:-1 tvg-id="" tvg-name="ID: AniPlus" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/Aniplus.png" group-title="🎥",Aniplus 
https://cdn08jtedge.indihometv.com/dassdvr/107/aniplus/manifest.mpd

#EXTINF:-1 tvg-id="Animax.MACAN" tvg-name="Animax" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/animax.png" group-title="🎥",Animax
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=ecc5bc0e2dec4b9495db147278fb3904:ca86d9fdad6a8e9b1c13368d734e2095
https://atemecdnbalancer-voe.sysln.id/live/eds/AnimaxHD/mpd/AnimaxHD.mpd

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/arirang.png" group-title="🎥",ARIRANG WORLD
http://amdlive.ctnd.com.edgesuite.net/arirang_1ch/smil:arirang_1ch.smil/playlist.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/kbsworld.png" group-title="🎥",KBS WORLD
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=4dbd7f200e1f43c1a5a7b0bb4d753527:7fa839050222d118f97ba1f770f7d188
https://atemecdnbalancer-voe.sysln.id/live/eds/KBSWorldHD/mpd/KBSWorldHD.mpd

#EXTINF:0 tvg-id="" tvg-name="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/sone.png" group-title="🎥",ONE
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=a7e68d7c2667465f976361eb0d6bd0c1:32a856d04efbf93cee7b2c97643d7998
https://atemecdnbalancer-voe.sysln.id/live/eds/ONEHD/mpd/ONEHD.mpd

#EXTM3U x-tvg-url="https://i.mjh.nz/au/Sydney/epg.xml"
#EXTINF:-1 channel-id="mjh-abc-kids" tvg-id="mjh-abc-kids" tvg-logo="https://i.mjh.nz/.images/abc-kids.png" tvg-chno="22" group-title="🎥" , ABC Kids
https://c.mjh.nz/abc-kids.m3u8|user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-abc-tv-plus" tvg-id="mjh-abc-tv-plus" tvg-logo="https://i.mjh.nz/.images/abc-tv-plus.png" tvg-chno="22" group-title="🎥" , ABC TV Plus
https://c.mjh.nz/abc-tv-plus.m3u8|user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-abc-me" tvg-id="mjh-abc-me" tvg-logo="https://i.mjh.nz/.images/abc-me.png" tvg-chno="23" group-title="🎥" , ABC ME
https://c.mjh.nz/abc-me.m3u8

#EXTINF:-1 channel-id="mjh-abc-news" tvg-id="mjh-abc-news" tvg-logo="https://i.mjh.nz/.images/abc-news.png" tvg-chno="24" group-title="🎥" , ABC NEWS
https://c.mjh.nz/abc-news.m3u8|user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs" tvg-id="mjh-sbs" tvg-logo="https://i.mjh.nz/.images/sbs.png" tvg-chno="3" group-title="🎥" , SBS
https://i.mjh.nz/.r/sbs.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-viceland" tvg-id="mjh-sbs-viceland" tvg-logo="https://i.mjh.nz/.images/sbs-viceland.png" tvg-chno="31" group-title="🎥" , SBS VICELAND
https://i.mjh.nz/.r/sbs-viceland.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-food" tvg-id="mjh-sbs-food" tvg-logo="https://i.mjh.nz/.images/sbs-food.png" tvg-chno="33" group-title="🎥" , SBS Food
https://i.mjh.nz/.r/sbs-food.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-world-movies" tvg-id="mjh-sbs-world-movies" tvg-logo="https://i.mjh.nz/.images/sbs-world-movies.png" tvg-chno="32" group-title="🎥" , SBS World Movies
https://i.mjh.nz/.r/sbs-world-movies.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-nitv" tvg-id="mjh-sbs-nitv" tvg-logo="https://i.mjh.nz/.images/sbs-nitv.png" tvg-chno="34" group-title="🎥" , NITV
https://i.mjh.nz/.r/sbs-nitv.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-world-watch" tvg-id="mjh-sbs-world-watch" tvg-logo="https://i.mjh.nz/.images/sbs-world-watch.png" tvg-chno="35" group-title="🎥" , SBS World Watch
https://i.mjh.nz/.r/sbs-world-watch.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20

#EXTINF:-1 channel-id="mjh-sbs-chill" tvg-id="mjh-sbs-chill" tvg-logo="https://i.mjh.nz/.images/sbs-chill.png" group-title="🎥" , SBS Chill
https://i.mjh.nz/.r/sbs-chill.m3u8|x-forwarded-for=110.33.122.75&user-agent=Mozilla/5.0%20%28Windows%20NT%2010.0%3B%20Win64%3B%20x64%29%20AppleWebKit/537.36%20%28KHTML%2C%20like%20Gecko%29%20Chrome/98.0.4758.102%20Safari/537.36&seekable=0&referer=%20
#EXTINF:-1 tvg-name="" tvg-id="Dunia Sinema HD" tvg-logo="https://i.ibb.co.com/JQL4v0H/duniasinema.png" group-title="🎥",DUNIA SINEMA 🇲🇾 (1.8s)
#EXTVLCOPT:http-user-agent=VLC/3.2.21 LibVLC/3.2.21
https://unifi-live01.secureswiftcontent.com/UnifiHD/live27-1080FHD.m3u8

#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"OjNo+jhaBJaV/03jw2gJzQ", "kid":"/CPEQjVYVJkqJkkxoo/BxQ" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="121.unifi" ch-number="121" tvg-logo="https://playtv.unifi.com.my:7220/CPS/images/universal/film/logo/202208/20220816/20220816023117758jev.png" group-logo="" group-title="🎥",Siar 
https://unifi-live07.secureswiftcontent.com/UnifiHD/live31.mpd

#EXTINF:0 tvg-id="" tvg-name="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/axn.png" group-title="🎥",AXN
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1 
#KODIPROP:inputstream.adaptive.license_type=clearkey 
#KODIPROP:inputstream.adaptive.license_key=b7b00124894d4f1f8b91fba79160b896:bb236ab2b198c2ffd722817bfa74cd08 
https://atemecdnbalancer-voe.sysln.id/live/eds/AXNHD/mpd/AXNHD.mpd
 
#EXTINF:0 tvg-id="" tvg-name="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/dcch.png" group-title="🎥",Discovery Channel
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=27c8a08eabcd4bbc88eda3690cbf6aaf:bb078e32f6df14ca97bff5b8aee8caf5
https://atemeshield1-voe.sysln.id/live/eds/DiscoveryAsiaHD/mpd/DiscoveryAsiaHD.mpd

#EXTINF:0 tvg-id="" tvg-name="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/animalplanet.png" group-title="🎥",Animal Planet
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=fe0d35dd7f2045e58bfdfeea879a8ae9:6a61e84d6c9147aa68c06d68f1d7b218
https://atemecdnbalancer-voe.sysln.id/live/eds/AnimalPlanetHD/mpd/AnimalPlanetHD.mpd


#EXTINF:-1 group-title="🎥" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/hgtv.png" ,HGTV Asia
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=4d3d70298a8f442f9dee7c11a47c3edf:ff7a89f008a62664e5ebd821187296d1
https://atemecdnbalancer-voe.sysln.id/live/eds/HGTVHD/mpd/HGTVHD.mpd

#EXTINF:-1, group-title="🎥" tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/lovenature.png",Love Nature
https://d18dyiwu97wm6q.cloudfront.net/playlist.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/afn.png" group-title="🎥",Asian Food Network
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=367f9bf4d0684f109d74a9eeb68d32be:59983c58c1b0daa1dcc370f697ccaead
https://atemecdnbalancer-voe.sysln.id/live/eds/AFNHD/mpd/AFNHD.mpd



#EXTINF:-1, group-title="🎥" tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/t&t.png",Travel & Taste
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/80.0.3987.100 Safari/537.36
https://b27a6dd8a86c3e4ba93fbae22aaaac64.pmqrop.channel-assembly.mediatailor.ap-southeast-1.amazonaws.com/v1/channel/FAST_5/dash.mpd



#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/zee.png" group-title="🎥",ZEE BIOSKOP
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=70d0197a8aca42589cf5df6daa576d86:ebd47832fd7251a09e3cc8eb36790ad5
https://atemeshield1-voe.sysln.id/live/eds/ZeeBioskop/mpd/ZeeBioskop.mpd

#EXTINF:-1 tvg-name="" tvg-id="IMC" tvg-logo="https://images.indihometv.com/logo_imc_small.png" group-title="🎥",IMC
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=69646b755f3130303030303030303030:e4a2359b05563399f1d9adfce641724a
https://cdn08jtedge.indihometv.com/dassdvr/130/imc/manifest.mpd


#EXTINF:-1 tvg-logo="https://iptv.urfan.web.id/logo/transtv.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥", transtv
https://video.detik.com/transtv/smil:transtv.smil/index.m3u8

#EXTINF:-1 tvg-logo="https://iptv.urfan.web.id/logo/trans7.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥", trans7
https://video.detik.com/trans7/smil:trans7.smil/index.m3u8

#EXTINF:-1 tvg-id="RCTI.id" tvg-country="ID" tvg-language="Indonesian" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/rcti.png" group-title="🎥",RCTI
#EXTVLCOPT:http-referrer=https://www.rctiplus.com/
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=d386001215594043a8995db796ad9e9c:3404792cb4c804902acdc6ca65c1a298
https://d2xz2v5wuvgur6.cloudfront.net/out/v1/997ce8767b604fae9fce05379b3b8b3a/index.mpd
https://rcti-cutv.rctiplus.id/rcti-sdi-avc1_800000=7-mp4a_96000=1.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/gtv.png" group-title="🎥",GTV
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=036e85de0bb448eeb21d39ab300da48e:4c6f9b15dfab2a169b2b78a498c4d77d
https://d2tjypxxy769fn.cloudfront.net/out/v1/b8b9b1d5f80f45649b4a3619291551ab/index.mpd

#EXTINF:-1 tvg-id="MNCTV.id" tvg-country="ID" tvg-language="English;Indonesian" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/mnctv.png" group-title="🎥",MNC TV
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=c3004565365a42d08e3bde39a516d64e:dbfdc0967cfbbed01dba730c99d9c14a
https://d2xz2v5wuvgur6.cloudfront.net/out/v1/d6b026ad50f14b7f9af5ddd5450007d4/index.mpd
https://av-ch-cdn.mncnow.id/live/eds/MNCTV-HD/sa_dash/MNCTV-HD.mpd

#EXTINF:-1 tvg-id="MNCTV.id" tvg-country="ID" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/antv.png" group-title="🎥",ANTV
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=251c384e846841abafa1f7c723d57e66:e45b06a38cd261b74c5160f0912c042f
https://d84q7nw4qf3j3.cloudfront.net/out/v1/0a6c6b1534444ab4bd903af8761e6747/index.mpd

EXTINF:-1 tvg-id="ANTV.MACAN" tvg-name="ANTV" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/antv.png" group-title="🎥",ANTV
#EXTVLCOPT:http-referrer=https://www.dens.tv/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/117.0
http://op-group1-swiftservehd-1.dens.tv/s/s07/index.m3u8


#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/stduni.png" group-title="🎥",STUDIO UNIVERSAL
#EXTVLCOPT:http-referrer=https://www.visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:138.0) Gecko/20100101 Firefox/138.0
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=b4a7b3289eff493d8700becf2e2a1157:bfbcfcb8137dd565a7f4b5ce7800c1f0
https://d84q7nw4qf3j3.cloudfront.net/out/v1/dc63bd198bc44193b570e0567ff5b22c/index.mpd

#EXTINF:-1 group-title="🎥" tvg-logo="_______", GALAXY PREMIUM
#####KODIPROP:inputstreamaddon=inputstream.adaptive 
#####KODIPROP:inputstream.adaptive.manifest_type=dash 
#####KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey 
#####KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"5KI1mwVWM5nx2a385kFySg", "kid":"aWRrdV8xMDAwMDAwMDAwMA" },{ "kty":"oct", "k":"aiLzPud/q5azGP491+EzXQ", "kid":"c2N0djAwMDAwMDAwMDAwMA" },{ "kty":"oct", "k":"sZeAy9sLQthtNBUydZC2eQ", "kid":"aW5kb3NpYXIwMDAwMDAwMA" } ], "type":"temporary" }
#EXTINF:-1 tvg-
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2695.ts
#####https://cdn08jtedge.indihometv.com/dassdvr/133/galaxypremium/manifest.mpd

#EXTINF:-1 group-title="🎥" tvg-logo="_______", GALAXY
#####KODIPROP:inputstreamaddon=inputstream.adaptive 
#####KODIPROP:inputstream.adaptive.manifest_type=dash 
#####KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey 
#####KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"5KI1mwVWM5nx2a385kFySg", "kid":"aWRrdV8xMDAwMDAwMDAwMA" } ], "type":"temporary" }
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2694.ts
#####https://cdn08jtedge.indihometv.com/dassdvr/133/galaxy/manifest.mpd
#EXTINF:-1 tvg-id="" tvg-country="" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/org.png" group-title="🎥",ORIGINALS
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=33333f38930949b1af65b3361ad80d1d:b159847f9af0500738b01e91cf023e30
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
https://d3b0v7fggu5zwm.cloudfront.net/out/v1/e992e986a88346c18a5dcc4fbcdae6b9/index.mpd

#EXTINF:-1 tvg-id="" tvg-country="" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/unq.png" group-title="🎥",UNIQUES
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=5a6668f3a5d64338bce13307e5c570be:d0c76237c5ee38e7a420e9c83323023e
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
https://d3b0v7fggu5zwm.cloudfront.net/out/v1/bde0a6d8d3fd4d77ae5093ad2e6699dc/index.mpd

#EXTINF:-1 tvg-id="" tvg-country="" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/cng.png" group-title="🎥",CINEEDGE
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=c7b3852d9c84418f942923e41c31e633:ddb99755e0bebd98c92c7eab974bf161
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
https://d2xz2v5wuvgur6.cloudfront.net/out/v1/47c895ca72544fcfa4221c499b555a10/index.mpd

#EXTINF:-1 tvg-id="" tvg-country="" tvg-language="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/spx.png" group-title="🎥",SUPERIXX
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=1dc30f49888c4652897d9c998aa2cac1:8ccb6857157c1a01c5a47eb853f51aa2
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
https://d2tjypxxy769fn.cloudfront.net/out/v1/782400332c96440598260730a864bc6f/index.mpd



##EXTINF:-1 group-logo="" group-title="🎥" tvg-id="" tvg-logo="https://get.perfecttv.net/logo/hbohd.png" ,141 HBO
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=a098896d2b11c5f3906a993c3ba5c610:f3f842c54cc96cbbd0bcb96a4cb8a813
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=hbo


#EXTINF:-1 tvg-id="HBOHits" tvg-name="HBO Hits" group-title="🎥" group-logo="" tvg-logo="https://get.perfecttv.net/logo/hbohits.png",142 HBO HITS
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=5d600eb70944d681c26c1f48fbe61f10:796139ba05a2ab425f978c7fd98b4372
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=hbohits

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="414.astro" tvg-logo="https://get.perfecttv.net/logo/hbofamily.png" ,144 HBO Family  
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=2b9ff7cc1a3dc9fef47cc5773472d510:7e37588e893ab9252e505bd6dda35beb
#EXTVLCOPT:http-user-agent=Mozilla/5.0
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=hbofamily

#EXTINF:-1 tvg-id="Cinemax" tvg-name="CINEMAX HD" group-title="🎥" tvg-logo="https://get.perfecttv.net/logo/cinemax.png" group-logo="https://astrogo.astro.com.my/staticFiles/images/icons/fav-icon.png",145 CINEMAX
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=efdb2a8d39151cc39f4b51d762cf9c10:13cc535ad4a73201147863cac386cdd3
https://get.perfecttv.net/dash2.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=cinemax


#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="413.astro" tvg-logo="https://get.perfecttv.net/logo/showcase.png" ,146 Showcase Movies 
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_key=b8090c8361cc5cc5c1aac0ec2710de10:ca0d18538845bae2cb4f4a168036f174
https://get.perfecttv.net/astro_10802.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=showcase

#EXTINF:-1 group-logo="" group-title="🎥" tvg-id="474.unifi" ch-number="474" tvg-logo="https://get.perfecttv.net/logo/rockaction.png",147 Rock Action
#KODIPROP:inputstream.adaptive.manifest_type=dash
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=3dd653fc7aa1e3075b7f0233620df68f:8573791fa55bff03a3094ff559fc1407
https://get.perfecttv.net/mytv.mpd?username=vip_3klp0es8&password=wg3piwEs&channel=rockaction

#EXTINF:0 tvg-id="" tvg-name="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/trill.png" group-title="🎥",Thrill
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3325.181 Safari/537.36
#EXTVLCOPT:http-referrer=https://visionplus.id
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey
#KODIPROP:inputstream.adaptive.license_key=3ffab3471a994535bdf7fc663792f08b:6e82876474df025c39ae804ba738ff17
https://d2tjypxxy769fn.cloudfront.net/out/v1/3c619ecc120b46e999d1eaa627cc544f/index.mpd


#EXTINF:-1 tvg-id="401.astro" tvg-logo="httpss://raw.githubusercontent.com/mystery75/logo/main/HitsMoviesV2.png" group-logo="httpss://astrogo.astro.com.my/staticFiles/images/icons/astroLogo.png" group-title="🎥",Hits Movies    
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=12a34fccac944a19a14101a9009dae05:2d1543668411b31aec7269d889d4821c
https://atemecdnbalancer-voe.sysln.id/live/eds/HitsMoviesHD/mpd/HitsMoviesHD.mpd

#EXTINF:-1 group-title="🎥" tvg-logo="_______", CINEMA WORLD
#KODIPROP:inputstreamaddon=inputstream.adaptive 
#KODIPROP:inputstream.adaptive.manifest_type=dash 
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey 
#KODIPROP:inputstream.adaptive.license_key=69646b755f3130303030303030303030:e4a2359b05563399f1d9adfce641724a
https://cdn08jtedge.indihometv.com/dassdvr/134/cinemaworld/manifest.mpd


#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"BY3shFvTQBeKOI7dEEoBXg", "kid":"QPAZuGJB0j7wdWM/1/HpJw" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="ts210" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/MN%2B.png" group-logo="" group-title="🎥",MN+ 
https://times-ott-live.akamaized.net/mnplus_wv_drm/index.mpd
#####https://starshare.live:443/live/Winston123/Winston123/98847.ts
#####https://starshare.live:443/live/star123/star123/178.ts

#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"BY3shFvTQBeKOI7dEEoBXg", "kid":"QPAZuGJB0j7wdWM/1/HpJw" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="ts599" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/MNX.png" group-logo="" group-title="🎥",MNX
https://times-ott-live.akamaized.net/mnxhd_wv_drm/index.mpd
#####https://starshare.live:443/live/star123/star123/191.ts

#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key={ "keys":[ { "kty":"oct", "k":"BY3shFvTQBeKOI7dEEoBXg", "kid":"QPAZuGJB0j7wdWM/1/HpJw" } ], "type":"temporary" }
#EXTINF:-1 tvg-id="ts173" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/MoviesNow.png" group-logo="" group-title="🎥",Movies Now
https://times-ott-live.akamaized.net/moviesnow_wv_drm/index.mpd

#EXTINF:-1 tvg-id="" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/&flix.png" group-title="🎥",&flix  
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2685.ts

#EXTINF:-1 tvg-id="" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/&privé.png" group-title="🎥",&privé  
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2686.ts

#EXTINF:-1 tvg-id="" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/SonyPixV3.png" group-title="🎥",Sony Pix
https://tataplay.slivcdn.com/hls/live/2011748/PIXHD/master.m3u8
#####https://otttv.co.in/d2h/livestream/sony-pix-hd/

#EXTINF:-1 tvg-id="" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/StarMovies.png" group-title="🎥",Star Movies
http://83.142.30.171:8080/live/vip_3klp0es8/wg3piwEs/2687.ts
#KODIPROP:inputstream.adaptive.manifest_type=mpd
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=71cbdf02b595468bb77398222e1ade09:c3f2aa420b8908ab8761571c01899460
#EXTINF:-1 tvg-id="TAPMOVIES" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/0/06/TapMovies-ph.png" group-title="🎥",Tap Movies
https://qp-pldt-live-grp-06-prod.akamaized.net/out/u/cg_tapmovies_hd1.mpd

#KODIPROP:inputstream.adaptive.manifest_type=mpd
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=bee1066160c0424696d9bf99ca0645e3:f5b72bf3b89b9848de5616f37de040b7
#EXTINF:-1 tvg-id="TAPACTIONFLIX" tvg-logo="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDqmQyNNz--w-zNPAVx8fJLWG1xYahFiohWA&s" group-title="🎥",Tap Action Flix
https://qp-pldt-live-grp-06-prod.akamaized.net/out/u/cg_tapactionflix_hd1.mpd

#EXTINF:-1 tvg-id="CineLife.us" tvg-country="US" tvg-language="English" tvg-logo="https://play-lh.googleusercontent.com/TRj4zx_xl4QA3JO7DwqalxZwshmhxEzg0QzP1sT3Uv99p4izfj9S_yPZD4oVkFUxMNA" group-title="🎥",CineLife (1080p)
https://magnolia-cinelife.amagi.tv/playlist.m3u8

#EXTINF:-1 tvg-id="US18000163F" tvg-chno="770" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/Miramax.png" group-title="🎥",Miramax Movies Channel 
https://raw.githubusercontent.com/mystery75/m3u8/main/MIRAMAX.m3u8

#EXTINF:-1 tvg-id="99951377" tvg-name="AMC Thrillers" tvg-logo="https://image.xumo.com/v1/channels/channel/99951377/168x168.png?type=color_onBlack" group-title="🎥",AMC Thrillers
https://d3pxo1qcgzxtxs.cloudfront.net/10005/99951377/hls/playlist.m3u8?ads.xumo_channelId=99951377&ads.channelId=99951377&ads.csid=xumo_web_AMCAMCThrillers_ssai&ads._fw_is_lat=0&ads._fw_us_privacy=&ads._fw_coppa=0&ads._fw_did=:568e6389-eb70-45d7-bf33-1c2c7ea8b762&ads._fw_content_category=&ads._fw_content_language=en&ads._fw_content_genre=&ads._fw_content_rating=&ads.xumo_contentId=4174&ads.xumo_contentName=AMCAMCThrillers&ads.xumo_providerId=4174&ads.xumo_providerName=AMCAMCThrillers&ads._fw_deviceMake=GitHubAction&ads._fw_device_model=PythonScript&ads._fw_deviceType=3-Connected_TV&ads.xumo_platform=web&ads.appVersion=1.0.0&ads._fw_app_bundle=web.xumo.com&ads._fw_app_store_url=


#EXTINF:-1 tvg-id="USBD17000117B" tvg-logo="https://i.imgur.com/sOYAnTB.png" group-logo="" group-title="🎥", hi-yah
https://linear-59.frequency.stream/dist/xumo/59/hls/master/playlist.m3u8

#EXTINF:-1 tvg-id="USBD17000117B" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Comet_logo.svg/512px-Comet_logo.svg.png" group-logo="" group-title="🎥", comet
https://cvtv.cvalley.net/hls/KRCGComet/KRCGComet.m3u8

#EXTINF:-1 tvg-id="USBD17000117B" tvg-logo="https://i.imgur.com/KbmXdjm.png" group-logo="" group-title="🎥",freebie tv
https://d26pp4b7ojtlyn.cloudfront.net/scheduler/scheduleMaster/187.m3u8

#EXTINF:-1 tvg-id="USBD17000117B" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/MovieSphereByLionsgate.png" group-logo="" group-title="🎥",MovieSphere By Lionsgate
https://raw.githubusercontent.com/mystery75/m3u8/main/MSPHERE.m3u8

#EXTINF:-1 tvg-id="USBD1200007FE" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/OuterSphereByLionsgate.png" group-logo="" group-title="🎥",OuterSphere by Lionsgate
https://raw.githubusercontent.com/mystery75/m3u8/main/OUTERSPHERE.m3u8

#EXTINF:-1 tvg-id="USBD2500012DH" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/EbonyByLionsgate.png" group-logo="" group-title="🎥",Ebony by Lionsgate
https://raw.githubusercontent.com/mystery75/m3u8/main/EBONY.m3u8

#EXTINF:-1 tvg-id="5e20b730f2f8d5003d739db7-644c4bc17472b186783f35a0" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/HerSphereByLionsgate.png" group-logo="" group-title="🎥",HerSphere by Lionsgate
https://raw.githubusercontent.com/mystery75/m3u8/main/HERSPHERE.m3u8






#KODIPROP:inputstreamaddon=inputstream.adaptive 
#KODIPROP:inputstream.adaptive.manifest_type=dash 
#KODIPROP:inputstream.adaptive.license_type=org.w3.clearkey 
#KODIPROP:inputstream.adaptive.license_key={"2528892552c65b5399017c2f2a194ab7":"fc87001860c95eb094c2dd5fc2d2e2bd","3ef088eaf6685839a1d77c9bc89b1e20":"68c8566c7cb4400fac63d0abe8eea6d4","4518f2fc410a5327b26a26e8c0cebd17":"16da291229b2b68ded5419cc35339beb"}
#EXTINF:-1 tvg-id="" tvg-logo="https://raw.githubusercontent.com/mystery75/logo/main/StudioPremiere.png" group-title="🎥",Universal Premiere ᵒᵗᵗ
https://unipluslivedash.akamaized.net/universalpremiert0/manifest.mpd

#EXTINF:-1 tvg-id="GB2600015OS" tvg-logo="https://images-0.rakuten.tv/storage/global-live-channel/translation/artwork_negative/0511ea59-1994-43e7-805b-f1e40b5ddb91-action-movies-rakuten-tv-1646655463-width190-quality100.png" group-logo="" group-title="🎥",Rakuten Action ᴴᴰ 
https://raw.githubusercontent.com/mystery75/m3u8/main/RACTION.m3u8



#EXTINF:-1 tvg-id="GB2600020OP" tvg-logo="https://images-1.rakuten.tv/storage/global-live-channel/translation/artwork_negative/060e7294-6008-4924-9879-b5d67b191534-comedy-movies-rakuten-tv-1646655938-width190-quality100.png" group-logo=""  group-title="🎥",Rakuten Comedy ᴴᴰ 
https://raw.githubusercontent.com/mystery75/m3u8/main/RCOMEDY.m3u8

#EXTINF:-1 tvg-id="GB2600012R3" tvg-logo="https://images-2.rakuten.tv/storage/global-live-channel/translation/artwork_negative/fea19cee-698e-45e0-9a8f-4714181bd0f4-drama-movies-rakuten-tv-1646656997-width190-quality100.png" group-logo=""  group-title="🎥",Rakuten Drama ᴴᴰ  
https://raw.githubusercontent.com/mystery75/m3u8/main/RDRAMA.m3u8

#EXTINF:-1 tvg-id="GB2600017PX" tvg-logo="https://images-2.rakuten.tv/storage/global-live-channel/translation/artwork_negative/97d6f2f2-b757-46c2-8d8c-f78b084b1220-family-rakuten-tv-1646657558-width190-quality100.png" group-logo=""  group-title="🎥",Rakuten Family ᴴᴰ 
https://raw.githubusercontent.com/mystery75/m3u8/main/RFAMILY.m3u8

#EXTINF:-1 tvg-id="GB2600018PD" tvg-logo="https://images-2.rakuten.tv/storage/global-live-channel/translation/artwork_negative/bd059380-7181-47a0-8f7c-e20a86788a99-top-movies-rakutentv-1646658125-width190-quality100.png" group-logo=""  group-title="🎥",Rakuten Top Movies ᴴᴰ  
https://raw.githubusercontent.com/mystery75/m3u8/main/RTOPMOVIES.m3u8

#EXTINF:-1 tvg-id="GB2600014LQ" tvg-logo="https://images-0.rakuten.tv/storage/global-live-channel/translation/artwork-negative/287ea9f7-b2da-42fd-8ffa-b636eb08b5b2-width190-quality100.png" group-logo=""  group-title="🎥",Rakuten Romance ᴴᴰ  
https://jmp2.uk/sam-GB2600014LQ.m3u8

#EXTINF:-1 tvg-id="GB2600013BO" tvg-logo="https://images-3.rakuten.tv/storage/global-live-channel/translation/artwork-negative/3bae481e-2c87-4e98-85b3-2a1ad67ffb8b-width200-quality90.png" group-title="🎥" tvg-chno="4975",Rakuten Sci-Fi ᴴᴰ
https://jmp2.uk/sam-GB2600013BO.m3u8









#EXTINF:-1 tvg-logo="https://liquipedia.net/commons/images/5/57/DouyuLOGO.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥", 20415
https://hls1a-akm.douyucdn.cn/live/20415rnWbjg6Ex1K_900/playlist.m3u8?wsAuth=6fdc34a0fcaf1838b707a8de87f18527&token=web-h5-0-20415-b6774b3b3249db1717d0c07d4ce9a1bbd846dc8a189891b6&logo=0&expire=0&did=454ac73f2eb970914801dd8e00091601&ver=Douyu_222082905&pt=2&st=0&sid=355523749&origin=tct&mix=0&isp=

#EXTINF:-1 tvg-logo="https://i.imgur.com/ACEbGD5.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",localish
https://apollo.production-public.tubi.io/live/ac-localish.m3u8

#EXTINF:-1 tvg-logo="https://i.imgur.com/bKpligT.png" group-logo="https://www.washingtonblade.com/content/files/2020/01/QUEER_STREAMING_SERVICE_ADOPTS-LGBT_TOKEN_FEATURED_WB_10012020-e1578680670538.jpeg" group-title="🎥", revry her
https://linear-73.frequency.stream/mt/brightcove/73/hls/master/playlist.m3u8

#EXTINF:-1 tvg-logo="https://i.imgur.com/bKpligT.png" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥", revry 2
https://linear-5.frequency.stream/mt/brightcove/5/hls/master/playlist.m3u8

#EXTINF:-1 tvg-logo="https://images.samsung.com/is/image/samsung/assets/br/tvs/smart-tv/channel-list/Revry_Brasil_476x476circle.png?$ORIGIN_PNG$" group-title="🎥",revry
https://linear-181.frequency.stream/mt/brightcove/181/hls/master/playlist.m3u8

#EXTINF:-1 tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/SUKAN_RTM.jpg/220px-SUKAN_RTM.jpg" group-logo="https://ecentral.my/wp-content/uploads/2023/05/LOGO-MALAYSIA-MADANI-SAHAJA-768x1278.png" group-title="🎥",sukan
https://d25tgymtnqzu8s.cloudfront.net/smil:sukan/playlist.m3u8?id=4



#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://i.imgur.com/QwBGLzK.png" group-title="🎥",ava
https://familyhls.avatv.live/hls/stream.m3u8

#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/7/7d/Dubaione-logo.png" group-title="🎥",Dubai One (1080p)
https://dminnvllta.cdn.mgmlcdn.com/dubaione/smil:dubaione.stream.smil/chunklist.m3u8

#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/dubai_tv.jpg?v=6" group-title="🎥",Dubai TV
https://dmieigthvllta.cdn.mgmlcdn.com/dubaitvht/smil:dubaitv.stream.smil/chunklist.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc1.jpg?v=6" group-title="🎥",mbc
https://mbc1-enc.edgenextcdn.net/out/v1/0965e4d7deae49179172426cbfb3bc5e/index.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc3.jpg?v=6" group-title="🎥",mbc3
https://mbcbollywood-prod-dub-enc.edgenextcdn.net/out/v1/d5bbe570e1514d3d9a142657d33d85e6/index.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc4.jpg?v=6" group-title="🎥",mbc4
https://mbc4-prod-dub-enc.edgenextcdn.net/out/v1/c08681f81775496ab4afa2bac7ae7638/index.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc5.jpg?v=6" group-title="🎥",mbc5
https://mbc5-prod-dub-enc.edgenextcdn.net/out/v1/2720564b6a4641658fdfb6884b160da2/index.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc_drama.jpg?v=6" group-title="🎥",mbc drama
https://mbc1-enc.edgenextcdn.net/out/v1/b0b3a0e6750d4408bb86d703d5feffd1/index.m3u8
#EXTINF:-1 tvg-id="DubaiOne.ae" tvg-country="ARAB" tvg-language="English;Arabic" tvg-logo="https://www.elahmad.com/tv/mobiletv/images/mbc_drama_plus.jpg?v=6" group-title="🎥",mbc drama+
https://mbcplusdrama-prod-dub-enc.edgenextcdn.net/out/v1/97ca0ce6fc6142f4b14c0a694af59eab/index.m3u8


#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/tvrisport.png" group-title="sport",TVRI SPORT
https://ott-balancer.tvri.go.id/live/eds/SportHD/hls/SportHD-avc1_1500000=10003-mp4a_96000_eng=20003.m3u8

#EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/sportstars.png" group-title="sport",Sports Star 1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=39c4dc6704cf4ceea2fd4863b88d8a7d:4e9d7954c2ff46759289da4fc9f018ea
#EXTVLCOPT:http-referrer=https://www.visionplus.id/ 
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3325.181 Safari/537.36 
https://d2tjypxxy769fn.cloudfront.net/out/v1/89a6e4261cd7470f83e5869e90440cff/index.mpd
https://fta2-cdn-flr.visionplus.id/out/v1/89a6e4261cd7470f83e5869e90440cff/index.mpd

#EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/sportstar2.png" group-title="sport",Sports Star 2
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=911e72adf36946afbdbb4f80782a8394:08aec548a851ba64b7172ae7f05cb91c
#EXTVLCOPT:http-referrer=https://www.visionplus.id/ 
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3325.181 Safari/537.36 
https://d3b0v7fggu5zwm.cloudfront.net/out/v1/d2c68a3dfb644808b416bd90dcc92d5f/index.mpd
https://fta3-cdn-flr.visionplus.id/out/v1/d2c68a3dfb644808b416bd90dcc92d5f/index.mpd

#EXTINF:0 tvg-id="SoccerChannel.id" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/soccerch.png" group-title="sport",Soccer Channel
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=4035323a7fe64767ab8f3345ed9b93be:67377b8d429603f8bf30c161bda269e5
#EXTVLCOPT:http-referrer=https://www.visionplus.id/ 
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3325.181 Safari/537.36
https://fta4-cdn-flr.visionplus.id/out/v1/63c0da12bb4d48afbaf053f51dff2353/index.mpd

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/rtmsport.png" group-title="sport",RTM SPORT
#EXTVLCOPT:http-referrer=https://rtmklik.rtm.gov.my/.
https://d25tgymtnqzu8s.cloudfront.net/smil:sukan/playlist.m3u8?id=4

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/unifisports1.png" group-title="sport",UNIFI SPORTS 1
https://unifi-live05.secureswiftcontent.com/UnifiHD/live11.mpd

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/fight.png" group-title="sport",FIGHT SPORTS HD
#EXTVLCOPT:http-referrer=http://www.dens.tv/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/97.0.4692.99 Safari/537.36
http://op-group1-swiftservehd-1.dens.tv/h/h05/index.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/redbulltv.png" group-title="sport",REDBULL TV
https://rbmn-live.akamaized.net/hls/live/590964/BoRB-AT/master_1660.m3u8?xtreamiptv.m3u8

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/spotv.png" group-title="sport",SPOTV
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=e60ece8f0d9042fcb52508055ec48e5e:213f438bd4961cda987d41b7f154f1e5
https://atemecdnbalancer-voe.sysln.id/live/eds/SPOTVHD/mpd/SPOTVHD.mpd

#EXTINF:-1 tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/spotv2.png" group-title="sport",SPOTV 2
#EXTVLCOPT:http-user-agent=ExoPlayerDemo/2.15.1 (Linux; Android 13) ExoPlayerLib/2.15.1
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=e6ed3fdf6e9f491d9ead109fc0b00cfc:3bc6c45722eb5fa7b343de9bffc4f7c7
https://atemecdnbalancer-voe.sysln.id/live/eds/SPOTV2HD/mpd/SPOTV2HD.mpd

#EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/eplnews.png" group-title="sport",EPL News
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=002046c9a49b9ab1cdb6616bec5d26c3:d2f92f6b7edc9a1a05d393ba0c20ef9e
https://fsly.stream.peacocktv.com/Content/CMAF_CTR-4s/Live/channel(vc1021n07j)/master.mpd

#EXTINF:0 tvg-id="SoccerChannel.id" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/truepre2.png" group-title="sport",EPL 1
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Linux; Android 7.1.2; TV BOX Build/NHG47L) AppleWebKit/537.36 (KHTML เช่น Gecko) Chrome/56.0.2924.87 Safari/537.36
#EXTVLCOPT:http-referrer=https://github.com/
https://raw.githubusercontent.com/Jonjoni123/m3u8/master/Epl2.m3u8

EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/tnt1.png" group-title="sport",TNT Sports 1
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (iPhone; CPU iPhone OS 13_2_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.3 Mobile/15E148 Safari/604.1
#EXTVLCOPT:http-referrer=https://pkpakiplay.xyz
https://nfsnew.newkso.ru/nfs/premium31/mono.m3u8

EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/tnt2.png" group-title="sport",TNT Sports 2
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (iPhone; CPU iPhone OS 13_2_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.3 Mobile/15E148 Safari/604.1
#EXTVLCOPT:http-referrer=https://pkpakiplay.xyz
https://nfsnew.newkso.ru/nfs/premium32/mono.m3u8

EXTINF:0 tvg-id="" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/tnt2.png" group-title="sport",TNT Sports 3
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (iPhone; CPU iPhone OS 13_2_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.3 Mobile/15E148 Safari/604.1
#EXTVLCOPT:http-referrer=https://pkpakiplay.xyz
https://nfsnew.newkso.ru/nfs/premium33/mono.m3u8

#EXTINF:0 tvg-id="SoccerChannel.id" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/bein1.png" group-title="sport",Bein 1
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.manifest_type=mpd
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=3ae6a430c1b8420ea280e317143d8d3a:142473ee925db0db0083c74a178c8298
https://d6m3sfa7e58z5.cloudfront.net/out/v1/3b0660e05eed4d769521eb0275aab3ab/index.mpd

#EXTINF:0 tvg-id="SoccerChannel.id" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/bein2.png" group-title="sport",Bein 2
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=3d756d566ca94e6499518ffb1474d5d0:dbe4ad6803e74739b8f954d23cc58e7b
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
https://d6m3sfa7e58z5.cloudfront.net/out/v1/cfca527d0f16403396a71b2d3d54c32f/index.mpd

#EXTINF:0 tvg-id="SoccerChannel.id" tvg-logo="https://raw.githubusercontent.com/Iqbalbala/CHANNEL/refs/heads/main/bein3.png" group-title="sport",Bein 3
#EXTVLCOPT:http-referrer=https://visionplus.id/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
#KODIPROP:inputstream.adaptive.license_type=clearkey
#KODIPROP:inputstream.adaptive.license_key=344d320ca45641a88cf002db351ed9a4:246cc6ee7ab235cb824ed3b904b7040b
https://d6m3sfa7e58z5.cloudfront.net/out/v1/a265695db5cb461095cbfefc02ad793b/index.mpd

EXTINF:-1 tvg-logo="https://www.appcreator24.com/srv/imgs/seccs/20392732_ico.png?ts=1654805856" group-title="sport",Sony Ten 1
KODIPROP:inputstream.adaptive.license_type=clearkey
KODIPROP:inputstream.adaptive.license_key=ce17264b317db108f19cdc11aa1a9e66:a21188aee8fc5c56d016fcffcc6b2295
https://dai.google.com/linear/hls/event/6WhVNGKTRXyu588zZv1Lkg/master.m3u8

EXTINF:-1 tvg-logo="https://www.appcreator24.com/srv/imgs/seccs/20392768_ico.png?ts=1654805937" group-title="sport",Sony Ten 2
KODIPROP:inputstream.adaptive.license_type=clearkey
KODIPROP:inputstream.adaptive.license_key=ce17264b317db108f19cdc11aa1a9e66:a21188aee8fc5c56d016fcffcc6b2295
https://dai.google.com/linear/hls/event/LK-ik89MQIi_pWBbg74KNQ/master.m3u8

#EXTINF:-1 tvg-logo="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJTAdjOP3BtvEicrmy-BDLS-7uUKMG9U6Wfw&usqp=CAU" group-title="sport",LIVE 1
https://raw.githubusercontent.com/Iqbalbala/TVINTEK/refs/heads/main/Live.m3u8

#EXTINF:-1 tvg-logo="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJTAdjOP3BtvEicrmy-BDLS-7uUKMG9U6Wfw&usqp=CAU" group-title="sport",LIVE 2
https://raw.githubusercontent.com/Iqbalbala/TVINTEK/refs/heads/main/Live2.m3u8

#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/AmcOAIY.png", cine5
https://cdn-cine5tv.yayin.com.tr/cine5tv/cine5tv/playlist.m3u8

#EXTINF:-1 group-title="music" tvg-logo="https://i.ibb.co/Drx6fgZ/Logo-white.png",vivo
https://stream.vivotv.uy/hls/stream.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/Qu7t15Y.png",dlx dance
https://sdn-global-live-streaming-packager-cache.3qsdn.com/64733/64733_264_live.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/HimuPPb.png",dlx music
https://sdn-global-live-streaming-packager-cache.3qsdn.com/13456/13456_264_live.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/5edYPBO.png",xtra
https://streaming.social3.hr/ExtraTVudzdhr5/uUankWqpXD/1.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/Ft24x5T.png",mooz ro
https://rtmp.digitalbroadcast.ro/moozro/moozro.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/GwATd3Y.png",mooz hits
https://rtmp.digitalbroadcast.ro/moozhits/moozhits.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/aX70RD2.png",mooz dance
https://rtmp.digitalbroadcast.ro/moozdance/moozdance.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/E9ha9Or.png",popstar
https://muzzik-live.morescreens.com/mts-3/playlist.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/9dz8MsD.png",tiktak
https://muzzik-live.morescreens.com/mts-a5/playlist.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/9dz8MsD.png",elektro
https://muzzik-live.morescreens.com/mts-9/playlist.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/GuM4GnX.png",now rock
https://lightning-now90s-samsungnz.amagi.tv/playlist.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/LQB6G3s.jpg",pop world tv
https://janus.xpbroadcasting.com:8443/hls/popworld.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/Z7HUU7V.png",ru tv
https://hls-03-video.webcaramba.com/rutv/live.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/rFQuAEv.png",stz tv
https://cloudvideo.servers10.com:8081/stztelebista/index.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/DLIbUMx.png",urban
https://cdn-apse1-prod.tsv2.amagi.tv/linear/amg01076-lightningintern-traceurban-samsungnz/playlist.m3u8
#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/Vvxz6KX.png",trace hits
https://d35j504z0x2vu2.cloudfront.net/v1/master/0bc8e8376bd8417a1b6761138aa41c26c7309312/trace-uk/encrypted.m3u8

#EXTINF:-1 group-title="music" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Radio_m2o_-_Logo_2019.svg/512px-Radio_m2o_-_Logo_2019.svg.png",m2o
https://4c4b867c89244861ac216426883d1ad0.msvdn.net/live/S62628868/uhdWBlkC1AoO/playlist.m3u8

#EXTINF:-1 group-title="music" tvg-logo="https://i.imgur.com/jxuwGRi.png",xite
https://xite-samsung-de.amagi.tv/playlist.m3u8

#EXTINF:-1 tvg-logo="https://i.ibb.co/db3J7xh/1-music-channel-logo-FB300-DCF9-A-seeklogo-com.png" group-title="music ",1 Music
http://hz1.teleport.cc/HLS/HD.m3u8

#EXTINF:-1 tvg-id="M2.ua" tvg-country="RU;UA" tvg-language="Ukrainian" tvg-logo="https://www.lyngsat.com/logo/tv/mm/m2-ua.png" group-title="music",M2 (540p)
http://live.m2.tv/hls3/stream.m3u8

#EXTINF:-1 tvg-name="" tvg-id="SEC Network" tvg-logo="https://play-lh.googleusercontent.com/RJ49IeJve4VPALBXqrqJGeAYOEoLQIZZ4zWwtJhofisng6ZYwGemZ-VXCx9ZQ-u7fw" group-title="music",cinemarama
https://5d00db0e0fcd5.streamlock.net/7062/7062/playlist.m3u8

#EXTINF:-1 group-title="music" tvg-logo="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR46L9X34ta5c2AsXKOxjTJEajcOyJ79fjruA&usqp=CAU",now90s
https://lightning-now90s-samsungnz.amagi.tv/playlist.m3u8







     









#EXTINF:-1 tvg-id="701" tvg-name="Fashion TV" tvg-logo="http://epg.51zmt.top:8000/tb1/gt/faguoshishang.png" group-title="music",Fashion TV
https://fash2043.cloudycdn.services/slive/ftv_ftv_4k_hevc_73d_42080_default_466_hls.smil/playlist.m3u8
#EXTINF:-1 tvg-id="701" tvg-name="Fashion TV" tvg-logo="http://epg.51zmt.top:8000/tb1/gt/faguoshishang.png" group-title="music",FTV
https://fash1043.cloudycdn.services/slive/ftv_midnite_secrets_adaptive.smil/chunklist_b1300000_t64MzYwcA==.m3u8
#EXTINF:-1 tvg-id="701" tvg-name="Fashion TV" tvg-logo="http://epg.51zmt.top:8000/tb1/gt/faguoshishang.png" group-title="music",KALOOPY
https://d35j504z0x2vu2.cloudfront.net/v1/manifest/0bc8e8376bd8417a1b6761138aa41c26c7309312/kaloopy/c02c9f82-fcc3-4ec2-9fb1-6169ce54e935/0.m3u8
#EXTINF:-1 tvg-id="701" tvg-name="Fashion TV" tvg-logo="http://epg.51zmt.top:8000/tb1/gt/faguoshishang.png" group-title="music",ROUGE
https://edge17.vedge.infomaniak.com/livecast/rougetv/chunklist_w968669534.m3u8

#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-superman-2025-lk21-d21.jpg.webp" group-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-superman-2025-lk21-d21.jpg.webp" group-title="21",suparman
https://cloud.hownetwork.xyz/xxx/MQ05KzcUFi9vY0d-dh0BHQA8BREdJhV5cTNGeScD/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/09/film-naked-gun-2025-lk21-1.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", naked gun
https://cloud.hownetwork.xyz/xxx/LBkiKyFUEDQsfEV8cQV7Dwc6DQIaISglcjAWL3cJYQ/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/05/film-mission-impossible-the-final-reckoning-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", mission imposible 2025
https://cloud.hownetwork.xyz/xxx/LxE6PSwWGWwrPAcjMEM_Oi4dZDotHFonKz8WIG5CMzspFycnKx5ac3JjQmEUdRQcDicREScdFHkgMBF6/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s1.lk21static.buzz/wp-content/uploads/2025/06/film-riff-raff-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", riff raff
https://cloud.hownetwork.xyz//yyy/MBEvKGgLFickfEV8cQV7Oi4NOy88Ji8eemYUKHAAMjs/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-f1-the-movie-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", F1
https://cloud.hownetwork.xyz/xxx/JElkOi0cWiwtJx4pbgJmandVHgsHPTseGg5PfiYGYDx7QA/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/08/film-sketch-2025-lk21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", sketch
https://cloud.hownetwork.xyz/xxx/MRMsOiYRWnNyY0JhFHUUHA4nEREmTEZwcjJPfg/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/08/film-elio-2025-lk21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", elio
https://cloud.hownetwork.xyz/xxx/JxQgIWhLR3N3fCAJAXQaBxoneC92SEV3djU/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/08/film-fixed-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", fixed
https://cloud.hownetwork.xyz/xxx/JBExKyFURXFwZFobBnISFB0gFnsmTE8lIDRE/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-smurfs-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", smurfs
https://cloud.hownetwork.xyz/xxx/MRU8PCMKWnNyY0JhFHUUHA4nEREmGEMlJ2ZEfQ/34/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-bride-hard-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", bride hard
https://cloud.hownetwork.xyz/xxx/IAogKiBUHyAwNVp-cwJjdRU9CwoJJi8eIGNDeSJTYW4/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://poster.lk21.party/wp-content/uploads/2025/07/film-almost-cops-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", almost cop
https://cloud.hownetwork.xyz/xxx/IxQkITYNWiItIQRhcQBkbW8PLCwhFSgZHWESeyAIYDl6/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s5.lk21static.buzz/wp-content/uploads/2025/01/film-man-with-no-past-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", man no past
https://cloud.hownetwork.xyz//yyy/3f48d48213660df0152f4908e0f72362/26/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s3.lk21static.buzz/wp-content/uploads/2025/04/film-a-working-man-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", workingman
https://cdn3.turboviplay.com/data/683fb84e62cae/683fb84e62cae.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s6.lk21static.buzz/wp-content/uploads/2025/06/film-shadow-force-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", shadow force
https://cloud.hownetwork.xyz/xxx/MRAoKioOWictIxQpbgJmandVPisnHRseGg5PfXoENzx1Gg/32/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s7.lk21static.buzz/wp-content/uploads/2025/04/film-in-the-lost-lands-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", lost land
https://cloud.hownetwork.xyz/xxx/KxZkOi0cWi0tIgNhL1E4PDFVe353TFojLiQFLTpvDgdySXp3dEpPJQ/32/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s3.lk21static.buzz/wp-content/uploads/2025/01/film-back-in-action-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", back in action
hhttps://cloud.hownetwork.xyz/xxx/IBkqJWgQGWwjMgMlLF57anJKfGMnFQIzIygoFBwENDx1HHt4IA/32/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s0.lk21static.buzz/wp-content/uploads/2024/06/film-boy-kills-world-2024-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", boy kills world
https://stream.hownetwork.xyz/yyy/boy-kills-world-2024-webdl_X_17491eaf/22/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s5.lk21static.buzz/wp-content/uploads/2025/05/film-fountain-of-youth-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", fountain of youth
https://cloud.hownetwork.xyz/xxx/JBc8IDEYHi9vPhFhOl8jLCpVe353TFo2JzMTIBxoCW51TXEodk9C/32/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s7.lk21static.buzz/wp-content/uploads/2025/05/film-the-legend-of-ochi-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", ochi
https://cloud.hownetwork.xyz/xxx/NhAsYykcECQsNVojJR05OyoRZHx1S0JsNTQVKC9vDgdzSHx_JhpEdQ/32/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s0.lk21static.buzz/wp-content/uploads/2025/03/film-fight-or-flight-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", fight or flight
https://cloud.hownetwork.xyz/xxx/ba0c5aa7fd81f3d6e943fa4cdecc254b/25/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s5.lk21static.buzz/wp-content/uploads/2023/08/film-corner-office-2023-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", CORNER OFFICE
https://cloud.hownetwork.xyz/xxx/ec131a864a1928f8235a016fd8cf549e/1/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s2.lk21static.buzz/wp-content/uploads/2025/06/film-the-amateur-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", AMARTEUR
https://cdn3.turboviplay.com/data1/6847b07591079/6847b07591079.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s2.lk21static.buzz/wp-content/uploads/2025/05/film-karate-kid-legends-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", karate kid
https://cloud.hownetwork.xyz//yyy/KRk7LzEcWiorNVogJlczNiYLZHx1S0JsNTQVKC9vDgd2HC99fBxCcw/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s6.lk21static.buzz/wp-content/uploads/2025/07/film-high-rollers-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", high rollers
https://cloud.hownetwork.xyz/xxx/KhEuJmgLGC0uNAU_bgJmandVPisnHRseGg4UfnYCNDp1TA/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s3.lk21static.buzz/wp-content/uploads/2025/07/film-guns-up-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", guns up
https://cloud.hownetwork.xyz//yyy/JQ0nPWgMB2xwYUV5bkczOiYUFhYaGBJ5JmRGKnE/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s7.lk21static.buzz/wp-content/uploads/2025/07/film-dora-and-the-search-for-sol-dorado-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", dora
https://cloud.hownetwork.xyz/xxx/Jhc7L2gYGSVvJR8pbkMzOTAbIWMjFgVsMT4bYSdfJDkmF2R8dUtCbDU0FSgvbw4HckAoeCAfQHY/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s1.lk21static.buzz/wp-content/uploads/2025/07/film-heads-of-state-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", head of state
https://cloud.hownetwork.xyz/xxx/Kh0oKjZUGCdvIgMtN1V7anJKfGMyHBUlLg4vEyZTYmx3HSt2/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s1.lk21static.buzz/wp-content/uploads/2025/06/film-from-the-world-of-john-wick-ballerina-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", ballerina
https://cloud.hownetwork.xyz//yyy/JAomI2gNHyRvJhg-L1R7NyRVIyEtF1o2KzIcYSFROjQnCiAgJFRFcXBkWjsmUjI0HSAWKyFIEyAjMkA/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s7.lk21static.buzz/wp-content/uploads/2025/04/film-g20-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", G20
https://cloud.hownetwork.xyz//yyy/LBc_ISYYHi8nfEV8cQV7Oi4NOy88Ji8eI2lPKHZUMGA/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s6.lk21static.buzz/wp-content/uploads/2025/04/film-novocaine-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", novocaine
https://cloud.hownetwork.xyz//yyy/136af2febe914252832a4e85aafbf7ef/31/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s2.lk21static.buzz/wp-content/uploads/2025/06/film-off-the-grid-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", off the grid
https://cloud.hownetwork.xyz//yyy/LR4vYzEREmwlIx4obgJmandVPisnHRseGg5DKCJUZzpzHQ/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s4.lk21static.buzz/wp-content/uploads/2025/06/film-kpop-demon-hunters-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", kpop demon hunter
https://cloud.hownetwork.xyz//yyy/KQgmPmgdEiwtP1okNl4iPTALZHx1S0JsNTQVKC9vDgcnSystJEpDdA/33/480.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s6.lk21static.buzz/wp-content/uploads/2025/07/film-m3gan-2-0-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", MEGAN 2
https://cloud.hownetwork.xyz/xxx/L0suLytURWxyfEV8cQV7Dwc6DQIaISggI2BAKnVVbw/33/804.m3u8
#EXTINF:-1 tvg-id="603.astro" tvg-logo="https://s1.lk21static.buzz/wp-content/uploads/2025/07/film-jurassic-world-rebirth-2025-lk21-d21.jpg.webp" group-logo="https://s7.lk21static.buzz/wp-content/uploads/2024/05/film-the-fall-guy-2024-lk21-d21.jpg.webp" group-title="21", JURASSIC WORLD REBIRTH
https://cloud.hownetwork.xyz/xxx/KA07LzYKHiJvJhg-L1R7KicaIDwxEVpzcmNCYQFcIwojARYWGk9HJCRoFChz/34/480.m3u8
