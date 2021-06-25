# mantisnft-release
Wordpress-Plugin for protected content by NFTKey of WAX (EOSIO)


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
[nft_content type="collection" collection="xusoxusoxuso;alien.worlds" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the template id "60869":*

<pre>
[nft_content type="template" collection="" template="60869" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the template id "60869" OR "113906":*

<pre>
[nft_content type="template" collection="" template="60869;113906" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the asset-id "1099545088338":*

<pre>
[nft_content type="asset" collection="" template="" asset="1099545088338" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>


*Shortcode [nft_content] for access by having an NFT of the asset-id "1099545088338" OR "1099539110613":*

<pre>
[nft_content type="asset" collection="" template="" asset="1099545088338;1099539110613" ] ...your protected content (with other wordpress-shortcodes maybe) [/nft_content]
</pre>
