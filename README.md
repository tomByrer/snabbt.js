# snabbt.js

Fast animations with Javascript and CSS transforms(Work in progress)

**Docs**

[Documentation](http://daniel-lundin.github.io/snabbt.js/)

**Demos**

- [Card formations](http://daniel-lundin.github.io/snabbt.js/cards.html)
- [Crazy sticks](http://daniel-lundin.github.io/snabbt.js/sticks.html)

## Releases
The initial release is out. Would love some feedback on things that can be improved. The release(and future ones) can be found in the release section

- **0.3.0** - Memory optimizations, improved Matrix API, better UMD wrappers
- **0.2.0** - Added support for RequireJS and browserify. Published to npm and bower
- **0.1.0** - Initial beta release
- **0.2.0** - Added support for RequireJS and browserify. Published to npm and bower

## Get it
snabbt is available with AMD-support, CommonJS-support and as a global module.

### Package managers
```
bower install snabbt.js
npm install snabbt.js
```

### CDNs

```
https//cdnjs.com/libraries/snabbt.js
https://www.jsdelivr.com/#!snabbt
```
## Browser Support

<table>
  <tbody>
    <tr>
      <td><img src="http://ie.microsoft.com/testdrive/ieblog/2010/Sep/16_UserExperiencesEvolvingthebluee_23.png" height="40"></td>
      <td><img src="http://img3.wikia.nocookie.net/__cb20120330024137/logopedia/images/d/d7/Google_Chrome_logo_2011.svg" height="40"></td>
      <td><img src="http://media.idownloadblog.com/wp-content/uploads/2014/06/Safari-logo-OS-X-Yosemite.png" height="40"></td>
      <td><img src="http://th09.deviantart.net/fs71/200H/f/2013/185/e/b/firefox_2013_vector_icon_by_thegoldenbox-d6bxsye.png" height="40"></td>
      <td><img src="http://upload.wikimedia.org/wikipedia/commons/d/d4/Opera_browser_logo_2013.png" height="40"></td>

    </tr>
    <tr>
      <td align="center">10+</td>
      <td align="center">✓</td>
      <td align="center">✓</td>
      <td align="center">✓</td>
      <td align="center">✓</td>
    </tr>
  </tbody>
</table>

Note: IE does not support the transform-style: preserve-3d property. This prevents nesting 3D transformed elements.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## TODOS

 - Improve documentation

[MIT License](LICENSE.txt) © 2015 Daniel Lundin (http://twitter.com/danielundin).
