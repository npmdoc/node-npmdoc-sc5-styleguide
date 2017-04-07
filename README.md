# api documentation for  [sc5-styleguide (v1.5.0)](https://github.com/SC5/sc5-styleguide#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sc5-styleguide.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sc5-styleguide) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sc5-styleguide.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sc5-styleguide)
#### Styleguide generator is a handy little tool that helps you generate good looking styleguides from stylesheets using KSS notation.

[![NPM](https://nodei.co/npm/sc5-styleguide.png?downloads=true)](https://www.npmjs.com/package/sc5-styleguide)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sc5-styleguide_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SC5"
    },
    "bin": {
        "styleguide": "./bin/styleguide"
    },
    "bugs": {
        "url": "https://github.com/SC5/sc5-styleguide/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.3.2",
        "basic-auth-connect": "~1.0.0",
        "bemto.pug": "^2.1.0",
        "body-parser": "~1.14.1",
        "chalk": "~1.1.1",
        "cheerio": "^0.19.0",
        "cookie-parser": "~1.4.0",
        "css": "~2.2.0",
        "cssnext": "^1.8.4",
        "express": "~4.13.0",
        "fs-extra": "^0.26.2",
        "gonzales-pe": "4.0.3",
        "gulp": "~3.9.0",
        "gulp-concat": "~2.6.0",
        "gulp-cssnext": "^1.0.1",
        "gulp-mustache": "~2.0.1",
        "gulp-postcss": "^6.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.3",
        "gulp-util": "~3.0.5",
        "kss": "~2.1.0",
        "lodash": "~3.10.1",
        "markdown-it": "^5.1.0",
        "minimatch": "~3.0.0",
        "minimist": "^1.2.0",
        "morgan": "~1.6.0",
        "node-localcache": "^0.1.3",
        "postcss": "^5.0.14",
        "postcss-advanced-variables": "^1.2.2",
        "postcss-color-alpha": "^1.0.3",
        "postcss-color-function": "^2.0.0",
        "postcss-conditionals": "^2.0.1",
        "postcss-custom-media": "^5.0.1",
        "postcss-import": "^8.0.2",
        "postcss-inline-comment": "^2.0.0",
        "postcss-mixins": "^4.0.0",
        "postcss-nested": "^1.0.0",
        "postcss-partial-import": "^1.3.0",
        "pug": "^2.0.0-beta6",
        "q": "~1.4.1",
        "run-sequence": "~1.1.0",
        "socket.io": "~1.4.0",
        "through2": "~2.0.0",
        "vinyl": "~1.1.0",
        "vinyl-fs": "~2.2.1",
        "yargs": "~3.30.0"
    },
    "description": "Styleguide generator is a handy little tool that helps you generate good looking styleguides from stylesheets using KSS notation.",
    "devDependencies": {
        "babel-core": "^6.7.2",
        "babel-preset-es2015": "^6.1.18",
        "babel-register": "^6.7.2",
        "babel-root-import": "^3.2.2",
        "chai": "~3.4.1",
        "conventional-changelog": "git://github.com/sc5/conventional-changelog.git#features/sc-styleguide",
        "coveralls": "~2.11.2",
        "del": "~2.1.0",
        "dependency-check": "~2.5.1",
        "gulp-babel": "^6.1.0",
        "gulp-bower": "~0.0.10",
        "gulp-doctoc": "^0.1.2",
        "gulp-istanbul": "~0.10.0",
        "gulp-jscs": "~3.0.2",
        "gulp-jshint": "~2.0.0",
        "gulp-mocha": "~2.2.0",
        "gulp-ng-annotate": "~1.1.0",
        "gulp-plumber": "~1.0.1",
        "gulp-rimraf": "^0.2.0",
        "istanbul": "~0.4.1",
        "jscs": "~2.6.0",
        "jshint": "~2.9.1",
        "karma": "~0.13.15",
        "karma-coverage": "~0.5.3",
        "karma-mocha": "~0.2.1",
        "karma-mocha-reporter": "~1.1.2",
        "karma-phantomjs-launcher": "~1.0.0",
        "karma-sinon-chai": "~1.1.0",
        "main-bower-files": "~2.9.0",
        "node-localcache": "^0.1.3",
        "phantomjs-prebuilt": "2.1.7",
        "proxyquire": "~1.7.3",
        "requirefrom": "~0.2.0",
        "sinon": "~1.17.2",
        "sinon-chai": "~2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e4e6360a4a5a77b12117bb616cd60eb832338998",
        "tarball": "https://registry.npmjs.org/sc5-styleguide/-/sc5-styleguide-1.5.0.tgz"
    },
    "files": [
        "bin/",
        "lib/",
        "test/",
        ".bowerrc",
        ".jscsrc",
        "demo-gulpfile.js",
        "bower.json",
        "CHANGELOG.md",
        "CHANGELOG_LATEST.md",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "1de24d490a0bbfc1220a9bdaad829f3d3259df8c",
    "homepage": "https://github.com/SC5/sc5-styleguide#readme",
    "keywords": [
        "styleguide"
    ],
    "license": "MIT",
    "main": "./lib/styleguide.js",
    "maintainers": [
        {
            "name": "hannu",
            "email": "hannu@sc5.io"
        },
        {
            "name": "jpbackman",
            "email": "juuso.backman@sc5.io"
        },
        {
            "name": "junaidrsd",
            "email": "junaid@sc5.io"
        },
        {
            "name": "matudelic",
            "email": "matu.eriksson@gmail.com"
        },
        {
            "name": "simkall",
            "email": "simon.kall@gmail.com"
        },
        {
            "name": "varya",
            "email": "mail@varya.me"
        }
    ],
    "name": "sc5-styleguide",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SC5/sc5-styleguide.git"
    },
    "scripts": {
        "build": "gulp build",
        "demo": "gulp --gulpfile ./demo-gulpfile.js watch",
        "depcheck": "dependency-check . --unused --no-dev --entry gulpfile.js --entry demo-gulpfile.js --entry lib/styleguide.js",
        "posttest": "gulp generate-coverage-report",
        "prepublish": "gulp build",
        "pretest": "gulp clean-coverage",
        "test": "gulp test"
    },
    "version": "1.5.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sc5-styleguide](#apidoc.module.sc5-styleguide)
1.  [function <span class="apidocSignatureSpan">sc5-styleguide.</span>addSection (options)](#apidoc.element.sc5-styleguide.addSection)
1.  [function <span class="apidocSignatureSpan">sc5-styleguide.</span>applyStyles ()](#apidoc.element.sc5-styleguide.applyStyles)
1.  [function <span class="apidocSignatureSpan">sc5-styleguide.</span>generate (options)](#apidoc.element.sc5-styleguide.generate)
1.  [function <span class="apidocSignatureSpan">sc5-styleguide.</span>server (options)](#apidoc.element.sc5-styleguide.server)



# <a name="apidoc.module.sc5-styleguide"></a>[module sc5-styleguide](#apidoc.module.sc5-styleguide)

#### <a name="apidoc.element.sc5-styleguide.addSection"></a>[function <span class="apidocSignatureSpan">sc5-styleguide.</span>addSection (options)](#apidoc.element.sc5-styleguide.addSection)
- description and source-code
```javascript
addSection = function (options) {
  var throughOpts = {
      objectMode: true,
      allowHalfOpen: false
    };

  // Parameters
  var args = minimist(process.argv.slice(2)),
    params = {
      name: args.name || args.n,
      order: args.order || args.o
    };

  var parsers = options && options.parsers || 'undefined';

  // Validate params

  if (!params.name) {
    gutil.beep();
    gutil.log(gutil.colors.red('Define name with --name=my-name'));
    return;
  }

  if (!params.order) {
    gutil.beep();
    gutil.log(gutil.colors.red('Define name with --order=1.2.3'));
    return;
  }

  params.order = params.order.toString();

  var sectionRegExp = /(Styleguide )([0-9]+(\.[0-9]+)*)/;

  var allFiles = [];

  var nearestSibling = null;

  function isLess(left, right) {
    left = left.split('.');
    right = right.split('.');

    var l = false;

    for (var i = 0; i < Math.max(left.length, right.length); i++) {
      if (parseInt(left[i]) < parseInt(right[i])) {
        l = true;
        break;
      }
      if (parseInt(left[i]) > parseInt(right[i])) {
        l = false;
        break;
      }
    }

    return l;
  }

  function getFinalZeros(number) {
     var match = number.match(/^(\d+(?:\.\d+)*?)((?:\.0)*)$/);
     return {
       full: number,
       pure: match[1],
       zeros: match[2]
     };
  }

<span class="apidocCodeCommentSpan">  /*function isEqual(left, right) {
    var findZeros = /^(\d+(?:\.\d+)*?)((?:\.0)*)$/;
    // Remove ending zeros
    left = left.match(findZeros);
    if (left !== null) {
      left = left[1];
    } else {
      return false;
    }
    right = right.match(findZeros);
    if (right !== null) {
      right = right[1];
    } else {
      return false;
    }

    return (left === right);
  }*/
</span>
  function ifBelongsToParent(parentSection, section) {
    var belongs = true;
    parentSection = parentSection && parentSection.split('.');
    section = section.split('.');

    parentSection && parentSection.forEach(function(val, n) {
      if (val !== section[n]) {
        belongs = false;
      }
    });
    return belongs;
  }

  function increaseSection(section, newSection, diff) {
    // remove final zeros
    var normalizedSection = getFinalZeros(section);
    var normalizedSectionArray = normalizedSection.pure.split('.');

    var normalizedNewSection = getFinalZeros(newSection);
    var normalizedNewSectionArray = normalizedNewSection.pure.split('.');

    // Shold increase the same register as there are in new section
    var registerIndex = normalizedNewSectionArray.length - 1;
    if (normalizedSectionArray[registerIndex]) {
      normalizedSectionArray[registerIndex] = parseInt(normalizedSectionArray[registerIndex]) + diff;
    }

    return normalizedSectionArray.join('.') + normalizedSection.zeros;
  }

  function changeNumber(blocks, order, fileIndex) {
    return blocks.map(function(block){
      if (!block.kss) {
        return block;
      }
      var match = block.kss.match(sectionRegExp);
      var currentNumber = match[2];

      if (isLess(currentNumber, order)) {
        return block;
      }

      var parentSection = order.split('.');
      parentSection.pop();
      parentSection = parentSection.join('.');

      if (!ifBelongsToParent(parentSection, currentNumber)) {
        return block;
      }

      /*if (isEqual(parentSection, currentNumber)) {
        console.log('isEqual', parentSection, currentNumber);
        return block;
      }*/

      var newVal = increaseSection(currentNumber, order, 1);

      block.kss = block.kss.replace(sectionRegExp, '$1' + newVal);
      allFiles[fileIndex].modified = true;

      return block;
    });
  }

  function bufferFileContents(file, enc, done) {

    this.push(file);

    var contents = file.contents.toString(),
      syntax = path.extname(file.path).substring(1),
      parser = parsers  ? parsers[syntax] : 'undefined',
      blocks = kssSplitter.getBlocks(contents, syntax, parser);

    // check if a block is nearest sibling;
    blocks.forEach(function(block, index) {
      if (!block.kss) {
        return;
      }
      var match = block.kss.match(sect ...
```
- example usage
```shell
...
### Adding new section in between

You may use 'addSection' helper in order to make it easier adding a new section (or subsection) in between of the existing. It shifts
 reference numbers of the following sections. To create a helping task, write this:

'''js
gulp.task("styleguide:addsection", function() {
  return gulp.src('path/to/components/**/*.less')
    .pipe(styleguide.addSection())
    .pipe(gulp.dest('path/to/components/'))
});
'''

Use this task with the parameters:

'''
...
```

#### <a name="apidoc.element.sc5-styleguide.applyStyles"></a>[function <span class="apidocSignatureSpan">sc5-styleguide.</span>applyStyles ()](#apidoc.element.sc5-styleguide.applyStyles)
- description and source-code
```javascript
applyStyles = function () {
  var throughOpts = {
    objectMode: true,
    allowHalfOpen: false
  }, stylesBuffer = '',
    pseudoStylesBuffer = '',
    atRulesBuffer = '';

  function bufferFileContents(file, enc, done) {
    var pseudoStylesPromise,
      atRulesPromise;

    // Make sure file goes through the next gulp plugin
    // jshint -W040
    this.push(file);
    // jshint +W040

    // Process only CSS files
    // For example gulp-ruby-sass generatsd sourcemaps to the stream that we do not want to include
    if (path.extname(file.path) !== '.css') {
      done();
      return;
    }

    // Add styles to common stylesheet
    stylesBuffer += file.contents.toString();

    // Create stylesheet that contains pseudo styles
    pseudoStylesPromise = Q.Promise(function(resolve) {
      pseudoStylesBuffer += pseudoSelectors.stylesFromString(file.contents.toString(), {
        source: file.path
      });
      resolve();
    });

    // Create stylesheet that contains at-rules
    atRulesPromise = Q.Promise(function(resolve) {
      atRulesBuffer += atRules.stylesFromString(file.contents.toString(), {
        source: file.path
      });
      resolve();
    });

    Q.all([pseudoStylesPromise, atRulesPromise]).then(function() {
      done();
    });
  }

  return through(throughOpts, bufferFileContents, function(cb) {
    this.push(new File({
      path: 'styleguide.css',
      contents: new Buffer(stylesBuffer)
    }));

    this.push(new File({
      path: 'styleguide_pseudo_styles.css',
      contents: new Buffer(pseudoStylesBuffer)
    }));

    this.push(new File({
      path: 'styleguide_at_rules.css',
      contents: new Buffer(atRulesBuffer)
    }));

    cb();
  }).on('end', function() {
    if (socketIsOpen()) {
      serverInstance[sgOptions.port].io.emitStylesChanged();
    }
  });
}
```
- example usage
```shell
...
});

gulp.task('styleguide:applystyles', function() {
return gulp.src('main.scss')
  .pipe(sass({
    errLogToConsole: true
  }))
  .pipe(styleguide.applyStyles())
  .pipe(gulp.dest(outputPath));
});

gulp.task('watch', ['styleguide'], function() {
// Start watching changes and update styleguide whenever changes are detected
// Styleguide automatically detects existing server instance
gulp.watch(['*.scss'], ['styleguide']);
...
```

#### <a name="apidoc.element.sc5-styleguide.generate"></a>[function <span class="apidocSignatureSpan">sc5-styleguide.</span>generate (options)](#apidoc.element.sc5-styleguide.generate)
- description and source-code
```javascript
generate = function (options) {
  var opt = common.sanitizeOptions(options),
    filesBuffer = {},
    throughOpts = {
      objectMode: true,
      allowHalfOpen: false
    },
    styleguideProcessors = _.extend(
        {
          10: replaceSectionReferences,
          20: generateSectionWrapperMarkup
        },
        opt.styleguideProcessors
    );
  sgOptions = opt; // Copy options into global

  function bufferFileContents(file, enc, done) {
    if (file.isNull()) {
      return;
    }
    if (file.isStream()) {
      return console.error('Styleguide does not support streams!');
    }

    // Exclude empty files
    if (file.contents.toString('utf8') !== '') {
      filesBuffer[file.path] = file.contents.toString('utf8');
      var hash = crypto.createHash('md5').update(file.path).digest('hex');
      fileHashes[file.path] = hash;
      fileHashes[hash] = file.path;
    }

    // Make sure file goes through the next gulp plugin
    // jshint -W040
    this.push(file);
    // jshint +W040
    done();
  }

  emitProgressStart();

  // A stream through which each file will pass
  return through(throughOpts, bufferFileContents, function(callback) {
      var _this = this,
        // Styleguide object to be built
        styleguide = {},
        // Parse KSS sections
        parseKSSPromise = kssParser.parseKssSections(filesBuffer, opt.kssOpt, opt.parsers),
        // Filter variable files
        // File paths are full absolute paths so we need to add wildcard prefix
        // Also empty wildcard should return all files
        variableFiles = opt.styleVariables ? filterFiles(filesBuffer, '**/' + opt.styleVariables) : filesBuffer,
        // Parse variable decarations from files
        parseVariablesPromise = variableParser.parseVariableDeclarationsFromFiles(variableFiles, opt);

      Q.all([parseKSSPromise, parseVariablesPromise]).spread(function(sections, variables) {
        styleguide.sections = sections;
        styleguide.variables = variables;

        // Extend config with Angular directives declared in KSS
        opt.filesConfig = angularFiles.add(opt.filesConfig, sections);

        function pushAllFiles() {
          return through.obj(function(file, enc, cb) {
            _this.push(file);
            cb();
          });
        }

        function processOverviewMarkdown(opt) {
          return Q.Promise(function(resolve) {
            if (!opt.overviewPath) {
              resolve();
            }
            markdown.getStream(opt.overviewPath)
              .pipe(rename(function(path) {
                path.basename = 'overview';
                path.extname = '.html';
              }))
              .pipe(pushAllFiles())
              .on('finish', resolve);
          });
        }

        options.enablePug && generatePugMarkup(styleguide, options);

        _.each(styleguideProcessors, function(processor) {
          processor(styleguide);
        });

        copyUsedOptionsToJsonConfig(opt, styleguide);
        appendUsedVariablesToEachBlock(opt, styleguide);
        addFileHashesAndReplaceAbsolutePaths(styleguide);

        // Create JSON containing KSS data
        _this.push(new File({
          path: 'styleguide.json',
          contents: new Buffer(JSON.stringify(styleguide))
        }));

        var stylesCompiled,
          overviewProcessed,
          filesCopied,
          favIcon,
          indexHtmlProcessed;

        overviewProcessed = processOverviewMarkdown(opt);
        var cssSrc = [distPath + '/css/styleguide-app.css', distPath + '/css/styleguide_helper_elements.css'];

        // Copy all files (except index.html) from dist from to output stream
        filesCopied = Q.Promise(function(resolve) {
          //gulp.src([distPath + '/**', '!' + distPath + '/index.html', + '!' + distPath + '**/*.css'])
          var copySrc = [distPath + '/**', '!' + distPath + '/index.html'];

          copySrc = copySrc.concat(cssSrc.map(function(item){
            return '!' + item;
          }));

          gulp.src(copySrc)
            .pipe(pushAllFiles())
            .on('finish', resolve); ...
```
- example usage
```shell
...
var gulp = require('gulp');
var styleguide = require('sc5-styleguide');
var sass = require('gulp-sass');
var outputPath = 'output';

gulp.task('styleguide:generate', function() {
  return gulp.src('*.scss')
    .pipe(styleguide.generate({
        title: 'My Styleguide',
        server: true,
        rootPath: outputPath,
        overviewPath: 'README.md'
      }))
    .pipe(gulp.dest(outputPath));
});
...
```

#### <a name="apidoc.element.sc5-styleguide.server"></a>[function <span class="apidocSignatureSpan">sc5-styleguide.</span>server (options)](#apidoc.element.sc5-styleguide.server)
- description and source-code
```javascript
server = function (options) {
  return startServer(options);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
