# 📱💬 TikTok Comment Scraper

Un programme Python qui utilise l'API TikTok pour récupérer les 20 derniers commentaires d'un compte TikTok, avec la date et le lien de la vidéo associée 📅🔗. Les résultats sont affichés dans le terminal pour une utilisation facile et rapide. Utilisez-le pour suivre les dernières réactions de vos amis et influenceurs préférés sur TikTok! 😎

## Installation

"git clone https://github.com/mcaandyy/TikCom
cd TikCom
python3 /.TikCom.py"

## Auteur

Ce projet a été créé par @mcaandyy

## Licence

Ce projet est sous licence [insérer la licence ici].

## Exemple de code

Voici un exemple de code Python pour utiliser l'API TikTok et récupérer les 20 derniers commentaires d'un compte:

```python
import requests

username = "mon_compte_tiktok"
url = f"https://www.tiktok.com/node/share/user/@{username}"

params = {
    "secUid": "",
    "userId": "",
    "maxCursor": "0",
    "minCursor": "0",
    "lang": "",
    "appId": "1233",
    "count": "20",
    "idType": 2,
    "region": "US",
    "priority_region": "",
    "sourceType": 12,
    "source": "",
    "verifyFp": "",
    "cleanTop": 0,
    "withPgc": 0,
    "withGoods": 0,
    "withFusionShop": 0,
    "withDouPlusEntry": 0,
    "withBackupData": 0,
    "withCommerceEntry": 0,
    "withStarModule": 0,
    "withLabrador": "",
    "withNav": 0,
    "withFeedInfo": "",
    "withVideo": 0,
    "withUser": 0,
    "withReco": 0,
    "mid": "",
    "needUserInfo": 0,
    "isBackup": "",
    "stitchEnable": 1,
    "extParam": "",
    "addressBookAccess": 0,
    "gpsAccess": 0,
    "batteryLevel": "",
    "appType": "m",
    "traffic_type": "wifi",
    "sw-version": "",
    "ts": "",
    "ab_version": "",
    "appTheme": "",
    "mcc_mnc": "",
    "clientudid": "",
    "deviceId": "",
    "openudid": "",
    "cdid": "",
   
