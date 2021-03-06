# Avatar Configuration

Waline, like Valine, currently uses [Gravatar][1] as the comment list avatar.

Please log in or register by yourself [Gravatar][1], then modify your avatar.

When commenting, just leave the email address you used when registering in [Gravatar][1].

Thanks for the mirroring service provided by `gravatar.loli.net`.

> f you modify your avatar and find that it has not been updated, please don't panic, because `gravatar.loli.net` has a cache period of 7 days, please wait quietly~

Currently there are 7 types of `default values` for `non-custom avatar`:

|       Value       |                                                                Demo                                                                 | Style                                               |
| :---------------: | :---------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------------- |
| Empty string:`''` |                   ![Gravatar official graphics](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40)                   | Gravatar official graphics                          |
|       `mp`        |                  ![Mystic man (a grayhead)](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=mp)                  | Mystic man (a grayhead)                             |
|    `identicon`    |                 ![Abstract geometry](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=identicon)                  | Abstract geometry                                   |
|    `monsterid`    |                   ![little monster](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=monsterid)                   | little monster                                      |
|     `wavatar`     |   ![A combination of different faces and backgrounds](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=wavatar)   | A combination of different faces and backgrounds    |
|    `robohash`     | ![a generated robot with different colors, faces, etc](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=robohash) | a generated robot with different colors, faces, etc |
|      `retro`      |               ![Eight-pixel retro portrait](//gravatar.loli.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=40&d=retro)               | Eight-pixel retro portrait                          |
|      `hide`       |                                                               &nbsp;                                                                | Hidden avatar                                       |

> The parameter value `hide` is supported at `v1.1.8-beta`.  
> If the value of `avatar` is not equal to one of the seven parameters, the default value is` mm`.

```js
new Valine({
    ...
    avatar:'' // (''/mp/identicon/monsterid/wavatar/robohash/retro/hide)
});
```

[1]:http://gravatar.com/