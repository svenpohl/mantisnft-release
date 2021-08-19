# mantisnft-release
Wordpress-Plugin for protected content by NFTKey of WAX (EOSIO)

**Please download the *mantisnft.zip* (latest version) and move the mantisnft-directory to your wordpress-plugin-directory!**

Publish your premium-content on Wordpress and make it accessible only for the owners of your NFT's (atomichub.io / WAX-Blockchain).

![screen1](https://user-images.githubusercontent.com/26022558/123674735-3a26e200-d842-11eb-9ad6-72268f629e62.png)

![screen2](https://user-images.githubusercontent.com/26022558/123674773-46ab3a80-d842-11eb-83bc-9e4e71bf15c2.png)

![screen3](https://user-images.githubusercontent.com/26022558/123674784-4b6fee80-d842-11eb-8673-7f0ad5461006.png)

Usage:
------

*Example-Content for your protected KeyNFT - content with wallet-login:*

<pre>
[eosio_login]  
[nft_info]<div style="background:#eeeeee;padding:10px;"><strong>This content is protected by a KeyNFT. If you have a XUSO-NFT on your wallet, you can access this area. Please login with your WAX-Account.</strong></div>[/nft_info][nft_content type="collection" collection="xusoxusoxuso" ]
Here is your protected content for your users. Put your greatest stuff ever in this area!
<iframe width="560" height="315" src="https://www.youtube.com/embed/V5xmTSiYvn4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
[/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the collection "xusoxusoxuso":*

<pre>
[nft_content type="collection" collection="xusoxusoxuso" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the collection "xusoxusoxuso" OR "alien.worlds":*

<pre>
[nft_content type="collection" collection="xusoxusoxuso;alien.worlds" ] ...your protected content [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the template id "60869":*

<pre>
[nft_content type="template" collection="" template="60869" ] ...your protected content [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the template id "60869" OR "113906":*

<pre>
[nft_content type="template" collection="" template="60869;113906" ] ...your protected content [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the asset-id "1099545088338":*

<pre>
[nft_content type="asset" collection="" template="" asset="1099545088338" ] ...your protected content [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the asset-id "1099545088338" OR "1099539110613":*

<pre>
[nft_content type="asset" collection="" template="" asset="1099545088338;1099539110613" ] ...your protected content [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the asset-id "1099545088338" OR "1099539110613":*

<pre>
[nft_content type="asset" collection="" template="" asset="1099545088338;1099539110613" ] ...your protected content [/nft_content]
</pre>





*Shortcode [nft_show_template] showing the asset from collection "xusoxusoxuso" and the template-ID "195931":*
The parameter "color" can set to white, this results in a white shadowed border.

<pre>
[nft_show_template collection="xusoxusoxuso" id="195931" color="white"]
</pre>




*Shortcode [claimdropbox] for showing the deposited claimdrops for the user.
The user will see his available claimdrops after login

<pre>
[eosio_login]  

[claimdropbox]
</pre>

Example-view:
<img width="712" alt="image" src="https://user-images.githubusercontent.com/26022558/130063363-47cc1172-c647-44c6-bd19-c33658f248d9.png">



