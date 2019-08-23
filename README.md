# FLO_Torrent
FLO_Torrent is a decentralized platform for torrent storage with verification of uploader

## Mission statement
The torrent technology is widely used by millions of people to share the files without the need for a centralized server. 
But yet, the torrent file itself is required to be stored in a website (server) for the users to spread the torrent.
Thus its not completely decentralized and any torrent can be removed by the torrent website provider.
Once a torrent is been removed from the torrent search websites, no client users can download that torrent anylonger.
Hence it is required to store the torrent file in a decentralized medium so that no once can remove the torrent's existance.

This project allows the torrent uploader to permanently store the torrent file in the decentralized blockchain.
Any torrent users can download the torrent files from the blockchain without the use of centralized server.

Since the Torrent file is stored in blockchain, no one can remove it from the blockchain. 
Thus any torrent file uploaded by users will be stored permantly and can be accessed by other users at anytime.

Another issue is to prevent fake uploaders to use the name of reputed uploader to upload the torrent pretending to them. 
In the FLO Torrent Project, the FLO_ID is used to upload the torrent to the blockchain. 
Hence the transaction is verifed for the signature of the valid FLO_ID user and no fake uploaders can use the FLO_ID of reputed torrent uploaders
Thus the uploader ID is verified as well as the idendity of the uploader is anonymous.

## FLO Torrent Uploader
FLO_torrentUploader is used to upload the torrent file to the blockchain.
### Requirements to Upload
1. A valid FLO ID (Public Address and Private Key Pair) 
2. Minimal fee to upload the torrent (Scales with the file of the torrent file)
### Instructions to Upload
1. Open the `FLO_torrentUploader.html` in a Web Browser
2. Enter Uploader's FLO_ID (FLO address)
3. Browse/Select the torrent file from the local storage.
4. Enter the Torrent name, type, description and tags in the respective fields
5. Click the `Upload torrent` button
6. The balance of the FLO_ID and the fee required to upload the will be displayed in alert box.
7. Confirm and Enter the Private key of the FLO_ID when prompted.
8. The torrent file will be uploaded to the blockchain and the reference txid will be displayed.

## FLO Torrentz
FLO_torrentz is used to view the list of torrents uploaded to the blockchain
### Instructions
1. Open the `FLO_Torrentz.html` in a web browser.
2. The torrent list will be retrived from the blockchain using API and stored in IDB (local browser storage).
3. Click on the Torrent which you wish to download. (The uploader FLO_ID will also be shown).
4. The Torrent file will be retrived from the blockchain using API and then you can open/save the torrent file.
5. Open the torrent file in any torrent client apps (such as Bittorrent) and download the files.

## Android
Android users can directly download the FLO_Torrent.apk and Install the app.
To download the apk : Click [View raw](https://github.com/ranchimall/FLO_Torrent/blob/master/FLO_Torrent.apk?raw=true)
