# Binance P2P alternative API 

A python Module to scrape Binance P2P data from https://p2p.binance.com/

I can also create an API to import this data into your Ms Excel 

If you're interested in getting the module or a costume service, please contact me through Rhzif@hotmail.com 


# Получение данных Binance P2P, поддерживаются Excel и Jupyter 

Модуль python для соскабливания данных Binance P2P с сайта https://p2p.binance.com/.

Я также могу создать API для импорта этих данных в ваш Ms Excel. 

Если вы заинтересованы в получении модуля или услуги, пожалуйста, свяжитесь со мной через Rhzif@hotmail.com. 


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YlFfYPNoo8M/0.jpg)](https://www.youtube.com/watch?v=YlFfYPNoo8M) 



![](https://attachment.outlook.live.net/owa/MSA%3ARhzif%40hotmail.com/service.svc/s/GetAttachmentThumbnail?id=AQMkADAwATY0MDABLTAyNDEtY2RjOC0wMAItMDAKAEYAAAOlOMFcHb6zSpeDjrP0%2BJ3OBwBBEERpF16nSaL1wjGKgxCIAAACAQkAAABBEERpF16nSaL1wjGKgxCIAAIDZWw0AAAAARIAEACWg4x4GDk2SJtkwseTwtVn&thumbnailType=2&isc=1&token=eyJhbGciOiJSUzI1NiIsImtpZCI6IkZBRDY1NDI2MkM2QUYyOTYxQUExRThDQUI3OEZGMUIyNzBFNzA3RTkiLCJ0eXAiOiJKV1QiLCJ4NXQiOiItdFpVSml4cThwWWFvZWpLdDRfeHNuRG5CLWsifQ.eyJvcmlnaW4iOiJodHRwczovL291dGxvb2subGl2ZS5jb20iLCJ1YyI6IjEwYzM3OTQ2ZTBiMTRkZDFhMTE0ODFmYWNjOWZhMzY0IiwidmVyIjoiRXhjaGFuZ2UuQ2FsbGJhY2suVjEiLCJhcHBjdHhzZW5kZXIiOiJPd2FEb3dubG9hZEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJpc3NyaW5nIjoiV1ciLCJhcHBjdHgiOiJ7XCJtc2V4Y2hwcm90XCI6XCJvd2FcIixcInB1aWRcIjpcIjE3NTkyMTg2NDIzMDg1NTJcIixcInNjb3BlXCI6XCJPd2FEb3dubG9hZFwiLFwib2lkXCI6XCIwMDA2NDAwMC0wMjQxLWNkYzgtMDAwMC0wMDAwMDAwMDAwMDBcIixcInByaW1hcnlzaWRcIjpcIlMtMS0yODI3LTQwOTYwMC0zNzg2Njk1MlwifSIsIm5iZiI6MTY1NzE0MDMxNCwiZXhwIjoxNjU3MTQwOTE0LCJpc3MiOiIwMDAwMDAwMi0wMDAwLTBmZjEtY2UwMC0wMDAwMDAwMDAwMDBAODRkZjllN2YtZTlmNi00MGFmLWI0MzUtYWFhYWFhYWFhYWFhIiwiYXVkIjoiMDAwMDAwMDItMDAwMC0wZmYxLWNlMDAtMDAwMDAwMDAwMDAwL2F0dGFjaG1lbnQub3V0bG9vay5saXZlLm5ldEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJoYXBwIjoib3dhIn0.DRTE_lavu-l0EB8ghGfpnT_ZrEcD7RFlpg6SR9yxNAqQMPGo3hjeERCDN4XFrYWBfGBpM3cGNkGaTwjexRj5BQoiNNEEbV9dPGbKjOQLAGUnIfBuBcqncBLnTv2-0Wff8mGuJgkL6IPwZSw5UCPq7FR62XfrftICUaL-Akcp2eIAMlIeVYGX9cMfHi_pEvRiljEWE0-JnM8UsT_p0ISb75kx45KNVym0GHlmSwvrDKwDGJRt02HevrB98CZTpWyPLUQos6dpHl0Ptmgy47N-hrmRcrwMM4pdwwa7ktI6puCUOIkAjMp14qsVbSWadGXZAd_GLogFb2euINqYKsC4_w&X-OWA-CANARY=U7kEMl4VJUGeIxJQkfG_UjBMrQeRX9oYuQb9t8MskRiiffHF1_Ug0MBIWY7kArOtjy0hgugNkoY.&owa=outlook.live.com&scriptVer=20220624003.17&animation=true)


![](https://attachment.outlook.live.net/owa/MSA%3ARhzif%40hotmail.com/service.svc/s/GetAttachmentThumbnail?id=AQMkADAwATY0MDABLTAyNDEtY2RjOC0wMAItMDAKAEYAAAOlOMFcHb6zSpeDjrP0%2BJ3OBwBBEERpF16nSaL1wjGKgxCIAAACAQkAAABBEERpF16nSaL1wjGKgxCIAAIDZWw0AAAAARIAEAD1I91XsRueSK7VYX5h4qnR&thumbnailType=2&isc=1&token=eyJhbGciOiJSUzI1NiIsImtpZCI6IkZBRDY1NDI2MkM2QUYyOTYxQUExRThDQUI3OEZGMUIyNzBFNzA3RTkiLCJ0eXAiOiJKV1QiLCJ4NXQiOiItdFpVSml4cThwWWFvZWpLdDRfeHNuRG5CLWsifQ.eyJvcmlnaW4iOiJodHRwczovL291dGxvb2subGl2ZS5jb20iLCJ1YyI6IjEwYzM3OTQ2ZTBiMTRkZDFhMTE0ODFmYWNjOWZhMzY0IiwidmVyIjoiRXhjaGFuZ2UuQ2FsbGJhY2suVjEiLCJhcHBjdHhzZW5kZXIiOiJPd2FEb3dubG9hZEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJpc3NyaW5nIjoiV1ciLCJhcHBjdHgiOiJ7XCJtc2V4Y2hwcm90XCI6XCJvd2FcIixcInB1aWRcIjpcIjE3NTkyMTg2NDIzMDg1NTJcIixcInNjb3BlXCI6XCJPd2FEb3dubG9hZFwiLFwib2lkXCI6XCIwMDA2NDAwMC0wMjQxLWNkYzgtMDAwMC0wMDAwMDAwMDAwMDBcIixcInByaW1hcnlzaWRcIjpcIlMtMS0yODI3LTQwOTYwMC0zNzg2Njk1MlwifSIsIm5iZiI6MTY1NzE0MDYxNCwiZXhwIjoxNjU3MTQxMjE0LCJpc3MiOiIwMDAwMDAwMi0wMDAwLTBmZjEtY2UwMC0wMDAwMDAwMDAwMDBAODRkZjllN2YtZTlmNi00MGFmLWI0MzUtYWFhYWFhYWFhYWFhIiwiYXVkIjoiMDAwMDAwMDItMDAwMC0wZmYxLWNlMDAtMDAwMDAwMDAwMDAwL2F0dGFjaG1lbnQub3V0bG9vay5saXZlLm5ldEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJoYXBwIjoib3dhIn0.AOS1s8W-pgWnEAGnYCoIBtnkrtmNZuSAcp_FxFu3m9MjnqaSv0YxXhZ1ppG_nWQOgEs45jl8Tr5wR_T1OvrHNPrzuPLwxU8KAiwG3yr5zt6jRujqhVnPdftasElEZBj2PixHPhHHug1NO2J-FJVHWgPAI2j5LwJLX48QkadnY-a_84ba7qZ2N5Kg7e1UxohNvA1HAlrfKx_Z4COBsrEGEoORaJb7F1Vhssl-hgIMNEgDp4Odl23Te_PdobFwdL2ZdgBFQIr0_e-fRMc_yvx_6mlg3awCK-oVzq-qlQqP-ZVk0pCsZFddeP7_r4_On2AH6JQ7a7mWsI_-Kti9Pne5lg&X-OWA-CANARY=bco4-f94JEi6Ngczfnd4D4BwYiCRX9oYhGG9ikxnIq3SCUpS84_fOz-GQYRwKr7NBh5Gk61gszk.&owa=outlook.live.com&scriptVer=20220624003.17&animation=true)

 
![IMAGE ALT TEXT HERE](https://attachment.outlook.live.net/owa/MSA%3ARhzif%40hotmail.com/service.svc/s/GetAttachmentThumbnail?id=AQMkADAwATY0MDABLTAyNDEtY2RjOC0wMAItMDAKAEYAAAOlOMFcHb6zSpeDjrP0%2BJ3OBwBBEERpF16nSaL1wjGKgxCIAAACAQkAAABBEERpF16nSaL1wjGKgxCIAAIDZWw0AAAAARIAEADcbmILu80xRLoxgHalQJpE&thumbnailType=2&isc=1&token=eyJhbGciOiJSUzI1NiIsImtpZCI6IkZBRDY1NDI2MkM2QUYyOTYxQUExRThDQUI3OEZGMUIyNzBFNzA3RTkiLCJ0eXAiOiJKV1QiLCJ4NXQiOiItdFpVSml4cThwWWFvZWpLdDRfeHNuRG5CLWsifQ.eyJvcmlnaW4iOiJodHRwczovL291dGxvb2subGl2ZS5jb20iLCJ1YyI6IjEwYzM3OTQ2ZTBiMTRkZDFhMTE0ODFmYWNjOWZhMzY0IiwidmVyIjoiRXhjaGFuZ2UuQ2FsbGJhY2suVjEiLCJhcHBjdHhzZW5kZXIiOiJPd2FEb3dubG9hZEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJpc3NyaW5nIjoiV1ciLCJhcHBjdHgiOiJ7XCJtc2V4Y2hwcm90XCI6XCJvd2FcIixcInB1aWRcIjpcIjE3NTkyMTg2NDIzMDg1NTJcIixcInNjb3BlXCI6XCJPd2FEb3dubG9hZFwiLFwib2lkXCI6XCIwMDA2NDAwMC0wMjQxLWNkYzgtMDAwMC0wMDAwMDAwMDAwMDBcIixcInByaW1hcnlzaWRcIjpcIlMtMS0yODI3LTQwOTYwMC0zNzg2Njk1MlwifSIsIm5iZiI6MTY1NzE0MDYxNCwiZXhwIjoxNjU3MTQxMjE0LCJpc3MiOiIwMDAwMDAwMi0wMDAwLTBmZjEtY2UwMC0wMDAwMDAwMDAwMDBAODRkZjllN2YtZTlmNi00MGFmLWI0MzUtYWFhYWFhYWFhYWFhIiwiYXVkIjoiMDAwMDAwMDItMDAwMC0wZmYxLWNlMDAtMDAwMDAwMDAwMDAwL2F0dGFjaG1lbnQub3V0bG9vay5saXZlLm5ldEA4NGRmOWU3Zi1lOWY2LTQwYWYtYjQzNS1hYWFhYWFhYWFhYWEiLCJoYXBwIjoib3dhIn0.AOS1s8W-pgWnEAGnYCoIBtnkrtmNZuSAcp_FxFu3m9MjnqaSv0YxXhZ1ppG_nWQOgEs45jl8Tr5wR_T1OvrHNPrzuPLwxU8KAiwG3yr5zt6jRujqhVnPdftasElEZBj2PixHPhHHug1NO2J-FJVHWgPAI2j5LwJLX48QkadnY-a_84ba7qZ2N5Kg7e1UxohNvA1HAlrfKx_Z4COBsrEGEoORaJb7F1Vhssl-hgIMNEgDp4Odl23Te_PdobFwdL2ZdgBFQIr0_e-fRMc_yvx_6mlg3awCK-oVzq-qlQqP-ZVk0pCsZFddeP7_r4_On2AH6JQ7a7mWsI_-Kti9Pne5lg&X-OWA-CANARY=bco4-f94JEi6Ngczfnd4D4BwYiCRX9oYhGG9ikxnIq3SCUpS84_fOz-GQYRwKr7NBh5Gk61gszk.&owa=outlook.live.com&scriptVer=20220624003.17&animation=true)
 
