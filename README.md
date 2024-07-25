Release apk through CI/CD sample

1. Encode the Keystore File
   base64 /path/certificatescr.jks > certificatescr.jks.base64
   example:base64 /Volumes/Files/Altaf.SIL/2023/apks/rnd/certificatescr.jks > certificatescr.jks.base64
   
2. Go to your GitHub repository.
   Navigate to Settings > Secrets and variables > Actions. and put there ANDROID_KEYSTORE
   STORE_PASSWORD,KEY_PASSWORD & alias
