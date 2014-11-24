NamSor API
==========

NamSor Applied Onomastics API and SDKs (Extract Gender, Extract Origin, more...)

# Introduction
Applied onomastics is the science of proper names. Names are meaningful: they can be classified, sorted, filtered, corrected... This project is a placeholder to distribute open source SDKs for NamSor API. 

## NamSor API SDKs
Extract Gender SDK for Java, Scala, PHP, Python, C# [more]
http://restunited.com/releases/353822053726422518/wrappers

## GendRE API (Extract Gender)

GendRE is an Application Programming Interface (API) to determine the gender of a personal name on a -1 (Male) to +1 (Female) scale, for a given geography/locale.

The API automatically recognizes which culture to apply when assessing the gender of a personal name. Some examples: “Andrea Rossini” is most likely an Italian name and a male name, whereas “Andrea Parker” is most likely an anglosaxon name and a female name; 声涛周 is most likely male ; “O. Sokolova” is most likely female. Try those:

http://api.namsor.com/onomastics/api/json/gendre/Andrea/Rossini
http://api.namsor.com/onomastics/api/json/gendre/Andrea/Parker
http://api.namsor.com/onomastics/api/json/gendre/Jean/Durieux
http://api.namsor.com/onomastics/api/json/gendre/Jean/Allen

Still, we recommend passing additional geography/local context (as a ISO2 country code), if you know it - as it will improve the precision:

http://api.namsor.com/onomastics/api/json/gendre/John/Smith/us
http://api.namsor.com/onomastics/api/json/gendre/Julia/Roberts/us
http://api.namsor.com/onomastics/api/json/gendre/Olga/Sokolova/us
http://api.namsor.com/onomastics/api/json/gendre/Kjell/Bergqvist/se
http://api.namsor.com/onomastics/api/json/gendre/Alix/Dupond/fr
http://api.namsor.com/onomastics/api/json/gendre/声涛/周/cn
http://api.namsor.com/onomastics/api/json/gendre/淑珍/張/tw
http://api.namsor.com/onomastics/api/json/gendre/Илья/Ковальчук/ru
http://api.namsor.com/onomastics/api/json/gendre/בנימין/נתניהו/il
http://api.namsor.com/onomastics/api/json/gendre/معين/المرعبي/lb

# To contact us
contact@namsor.com
