NamSor API & SDK (V1-deprecated)
==============
NamSor API V1 will be discontinued on 31/12/2019. Please check out NamSor API V2 instead at www.namsor.com 
NamSor Applied Onomastics API and SDKs (Extract Gender, Extract Origin, more...). Applied onomastics is the science of proper names. Names are meaningful: they can be classified, sorted, filtered, corrected... This project is a placeholder to distribute open source SDKs for NamSor API. 

![NamSorSDK](https://raw.githubusercontent.com/namsor/namsor-api/master/2014_NamSor_Logo_500_250_SDK.png)

# NamSor API Homepage
* https://api.namsor.com/

## NamSor API SDK (RESTUnited)
* http://restunited.com/docs/guzycf9zsiro

## NamSor Java Client (on GitHub)
* https://github.com/namsor/namsor-java-client

## PowerBI Connector (on GitHub)
* https://github.com/namsor/namsor-powerbi-connector

## RapidMiner Add-On (on GitHub)
* https://github.com/namsor/rapidminer-onomastics-extension

## NamSor Origin API
NamSor Origin API will guess the likely country of origin of a personal name, based on the sociolinguistics of the name (language, culture). This is a coarse grain API, typically for marketing or social analytics.

The method for anthroponomical classification can be summarized as follow: judging from the name only and the publicly available list of all ~150k Olympic athletes since 1896 (and other similar lists of names), for which national team would the person most likely run? Here, the United-States are typically considered as a melting pot of other ‘cultural origins’: Ireland, Germany, etc. and not as a onomastic class on its own.

Register to get your API Key
* https://api.namsor.com/

NamSor Origin API is also available on Mashape API marketplace
* https://www.mashape.com/namsor/origin

## NamSor Gender API (Extract Gender)

NamSor Gender is an Application Programming Interface (API) to determine the gender of a personal name on a -1 (Male) to +1 (Female) scale, for a given geography/locale.

The API automatically recognizes which culture to apply when assessing the gender of a personal name. Some examples: “Andrea Rossini” is most likely an Italian name and a male name, whereas “Andrea Parker” is most likely an anglosaxon name and a female name; 声涛周 is most likely male ; “O. Sokolova” is most likely female. Try those:

* http://api.namsor.com/onomastics/api/json/gendre/Andrea/Rossini
* http://api.namsor.com/onomastics/api/json/gendre/Andrea/Parker
* http://api.namsor.com/onomastics/api/json/gendre/Jean/Durieux
* http://api.namsor.com/onomastics/api/json/gendre/Jean/Allen

Still, we recommend passing additional geography/local context (as a ISO2 country code), if you know it - as it will improve the precision:

* http://api.namsor.com/onomastics/api/json/gendre/John/Smith/us
* http://api.namsor.com/onomastics/api/json/gendre/Julia/Roberts/us
* http://api.namsor.com/onomastics/api/json/gendre/Olga/Sokolova/us
* http://api.namsor.com/onomastics/api/json/gendre/Kjell/Bergqvist/se
* http://api.namsor.com/onomastics/api/json/gendre/Alix/Dupond/fr
* http://api.namsor.com/onomastics/api/json/gendre/声涛/周/cn
* http://api.namsor.com/onomastics/api/json/gendre/淑珍/張/tw
* http://api.namsor.com/onomastics/api/json/gendre/Илья/Ковальчук/ru
* http://api.namsor.com/onomastics/api/json/gendre/בנימין/נתניהו/il
* http://api.namsor.com/onomastics/api/json/gendre/معين/المرعبي/lb

Register to get your API Key
* https://api.namsor.com/

NamSor Gender API is also available on Mashape API marketplace
* https://market.mashape.com/namsor/gendre-infer-gender-from-world-names

# To contact us
contact@namsor.com
