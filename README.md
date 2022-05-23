[![Is this project still maintained?](https://img.shields.io/maintenance/no/2022?style=for-the-badge)](https://github.com/badges/shields)
[![Donate](https://img.shields.io/badge/Donate-Patreon-blue?style=for-the-badge&logo=patreon)](https://www.leet.party)

## Due to the sunsetting of this project's core library libspotify, this project has been discontinued.

### What is Downtify?

Downtify is an open source Spofity downloader which makes it possible to download all your favourite songs and/or
playlists directly from Spotify.

![down-prem](https://user-images.githubusercontent.com/14614396/52458742-e7add380-2b69-11e9-8194-99e9131dc5b2.png)


A Spotify Premium account is required. 

This project was forked from [Shawak/downtify](https://github.com/Shawak/downtify) and was modified a bit.


### Usage

1. Paste in the text box the song(s) you want to download
2. Press `Enter` key to list the song(s) you have just pasted
3. Select the song(s) you want to download from that list
4. Press `Download`

### Configuration

To use Downtify, you need to clone/download this repo and edit the `config.xml` file:
```xml
<configuration>
  <username>username</username>
  <password>password</password>
  <language>en</language>
  <file_exists>SKIP</file_exists>
  <clientId>clientId</clientId>
  <clientSecret>clientSecret</clientSecret>
  <volume_normalization>false</volume_normalization>
</configuration>
```
`username` + `password` must be valid Premium user credentials.

`clientId` + `clientSecret` should be retrived from [here](https://developer.spotify.com/dashboard/applications).
* Log in with your Spotify account, create an app 
* Pick an ‘App name’ and ‘App description’ of your choice and mark the checkboxes.
* After creation, you see your ‘ClientId’ and you can click on "Show client secret" to unhide your 'clientSecret'.

### Downloading

You can download the latest version [here](https://github.com/L33Tech/downtify-premium/archive/master.zip).

### Known Issues ###

1. Playlists cannot be loaded at the moment. To download a full playlist follow this:
   - Open a playlist on Spotify
   - Select a single song
   - Press CTRL+A to select all songs
   - Press CTRL+C to copy all URIs to clipboard
   - Paste this in `downtify-premium` textbox
   - Press enter, and all of the songs will be loaded

### Bugs

Feel free to help develop this tool by reporting any issues to the [bug tracker](https://github.com/L33Tech/downtify-premium/issues).

### License

Downtify is licensed under the GNU General Public License v3, for more information please check out the [license information](https://github.com/L33Tech/downtify-premium/blob/master/LICENSE).

This project was forked from [elmundio87/downtify-premium](https://github.com/elmundio87/downtify-premium) which was forked from [eviabs/downtify-premium](https://github.com/eviabs/downtify-premium) which was forked from [Shawak/downtify](https://github.com/Shawak/downtify) and was modified a bit.


### Does it work?

As of May 2022, not anymore.
