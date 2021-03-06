<a name="0.1.5"></a>
### 0.1.5 (2014-07-18)


#### Bug Fixes

* **grunt:** configure proxy in hoodie callback ([15b2ce81](http://github.com/boennemann/zentodone/commit/15b2ce810b6c3b676bb3b8ae2e0a31c5220619c7))
* **travis:**
  * nodejitsu forgot our token, so we need to update it ([85bfb87b](http://github.com/boennemann/zentodone/commit/85bfb87b46f00da0d7c119740a68af4e39ad2c59))
  * travis changed their deploy behavior ([b0a49390](http://github.com/boennemann/zentodone/commit/b0a49390df7715146a08c320def357d45b6f75f2))


<a name="0.1.4"></a>
### 0.1.4 (2014-07-01)


#### Bug Fixes

* pull in latest bp fixes ([78bc08a3](http://github.com/boennemann/zentodone/commit/78bc08a323e70f2bf7a03d6f310dc146020d2caf))


#### Features

* **account:** allow anonymous use of the app ([b1a1c81b](http://github.com/boennemann/zentodone/commit/b1a1c81bf319841f41999e20f797633d9c2dc621))


<a name="0.1.3"></a>
### 0.1.3 (2014-05-30)


#### Bug Fixes

* **progress:** no unnecessary progress reporting ([41f9d92e](http://github.com/boennemann/zentodone/commit/41f9d92eecb17e0a0ede905e857cd74097f41930))


<a name="0.1.2-1"></a>
### 0.1.2-1 (2014-05-29)


<a name="0.1.2"></a>
### 0.1.2 (2014-05-28)


#### Bug Fixes

* **account:**
  * error handling for offline or downtime ([b4d9dd7f](http://github.com/boennemann/zentodone/commit/b4d9dd7f5642218c60a7a5117591f7c77cd43124))
  * handle failed signOut closes #10 ([60f00a26](http://github.com/boennemann/zentodone/commit/60f00a263aad0bbe2efe2118adcf724c85c0c15f))


<a name="0.1.1"></a>
### 0.1.1 (2014-05-26)


#### Bug Fixes

* **index:** all lowercase paths ([6a45b475](http://github.com/boennemann/zentodone/commit/6a45b475eecf5cdb073842d931eecad5ba7b802c))


<a name="0.1.0-0"></a>
### 0.1.0-0 (2014-05-26)


#### Bug Fixes

* **account:**
  * open links in new window ([f972c1ae](http://github.com/boennemann/zentodone/commit/f972c1ae17eaf7af129ba679251b8a4fa53ce53b))
  * attribute @leobabauta ([c292c2c7](http://github.com/boennemann/zentodone/commit/c292c2c7d055d22edd06a9c992f523ff215735e4))
* **sorttasks:** save back changed dueDates ([174429e3](http://github.com/boennemann/zentodone/commit/174429e31200b01939736513ad263057fe419537))
* **task:** bigger textarea by default ([e1640d19](http://github.com/boennemann/zentodone/commit/e1640d19c122d7dd15eac1879be076f7e5c88d7e))


#### Features

* **task:** show date information ([ea628a7c](http://github.com/boennemann/zentodone/commit/ea628a7c5de7eceedbb858f8b4486ec7a627dc41))


<a name="0.0.9-0"></a>
### 0.0.9-0 (2014-05-25)


#### Bug Fixes

* **font:** explicitly define font-family ([4408e43e](http://github.com/boennemann/zentodone/commit/4408e43e9cf7faad67b692c796c4d901e4c34dba))
* **grunt:** don't remove necessary whitespace ([0969ed70](http://github.com/boennemann/zentodone/commit/0969ed7036c13503d53c4db5ad2ee9398091e42c))
* **taskcell:** scroll works on Android/Chrome ([4f60faf7](http://github.com/boennemann/zentodone/commit/4f60faf7e9013e2eca295c9d1fd625da2842a43f), closes [#16](http://github.com/boennemann/zentodone/issues/16))


#### Features

* **account:** attribution and legal stuff ([719b6edc](http://github.com/boennemann/zentodone/commit/719b6edcb3fbb0d67f5757ec4cc2b6a0a1921c6d))


<a name="0.0.8-0"></a>
### 0.0.8-0 (2014-05-25)


#### Bug Fixes

* **inbox:**
  * hide done tasks closes #17 ([65192ba8](http://github.com/boennemann/zentodone/commit/65192ba824259358677f76ace12948a9ccf1fb76))
  * fix input behavior ([87e2feb7](http://github.com/boennemann/zentodone/commit/87e2feb7d85b447603a028a69b05d862fffa49ba))
  * bigger touch target and clearer message for input ([66dbbfdc](http://github.com/boennemann/zentodone/commit/66dbbfdc95ac8926fb9cf92f3042ac4b1c75268e))


#### Features

* empty views ([633ad520](http://github.com/boennemann/zentodone/commit/633ad520b08f50a0f20f09168a7699f99e7e986b))
* **br:** instructions ([06de2632](http://github.com/boennemann/zentodone/commit/06de2632e05b42a232c4c6264d2237499090461e))
* **inbox:**
  * instructions ([35ba6667](http://github.com/boennemann/zentodone/commit/35ba666725f3ddec4aadc0928beefb2a5931e251))
  * make task input more obvious ([a81b8084](http://github.com/boennemann/zentodone/commit/a81b8084c6ce3b0e816732a60991f248c300d188))
* **mit:** instructions ([9ebc67c0](http://github.com/boennemann/zentodone/commit/9ebc67c0a9cfbabf09576ec04ce10d7563c08f32))
* **progress:** track tutorial progress and hide if seen ([4c35815d](http://github.com/boennemann/zentodone/commit/4c35815dec2412aba3e9472b588c21e12f52482c))


<a name="0.0.7-0"></a>
### 0.0.7-0 (2014-05-22)


#### Bug Fixes

* **task:** overdue tasks now stick when marked as done in the current unit ([ce0add4e](http://github.com/boennemann/zentodone/commit/ce0add4eddde419177225c89893da81edee2aee3))
* **taskcell:** optimize overdue icon for landscape ([e149c91f](http://github.com/boennemann/zentodone/commit/e149c91ff1da8eace18e3653558d1fec4403e7bf))


#### Features

* **icons:** use custom built font for filesize ([5708d750](http://github.com/boennemann/zentodone/commit/5708d75098ad16717618f05f46d94e4b432bfdcc))
* **inbox:** "add to homescreen" popup ([930c0a92](http://github.com/boennemann/zentodone/commit/930c0a928280d58e3e365a2c28aca75a24824434))
* **taskcell:** improve overdue and done styles ([b9b463cd](http://github.com/boennemann/zentodone/commit/b9b463cd785cf6370aef9a51b1180a5047351a6d))


<a name="0.0.6-2"></a>
### 0.0.6-2 (2014-05-20)


#### Bug Fixes

* **task:** auto-growing textarea closes #8 ([fbeb20b3](http://github.com/boennemann/zentodone/commit/fbeb20b3f936d677ca5872388218d6419cc2a818))


<a name="0.0.6-1"></a>
### 0.0.6-1 (2014-05-16)


#### Features

* **logo:**
  * attribution ([0e922bc2](http://github.com/boennemann/zentodone/commit/0e922bc29808fa40b3aed5a9a82d4154c28f248e))
  * add logo, favicon, tile whatevs ([01988a15](http://github.com/boennemann/zentodone/commit/01988a1507b61c4a68f0e136459956eba3e4f4a8))


<a name="0.0.6-0"></a>
### 0.0.6-0 (2014-05-16)


#### Bug Fixes

* **inbox:**
  * don't fail in empty input ([302f16b7](http://github.com/boennemann/zentodone/commit/302f16b75b8c686e8ba937251f1cbe7e840a574e))
  * add new task on blur ([b4fdb501](http://github.com/boennemann/zentodone/commit/b4fdb501da7baa6a0ab2f05930765545ab3c1044), closes [#11](http://github.com/boennemann/zentodone/issues/11))
* **taskcell:**
  * reset styles after animation ([aa882aef](http://github.com/boennemann/zentodone/commit/aa882aef1d964270bd64940392f839c2c28ef174))
  * done tasks aren't swipeable ([43a53aa6](http://github.com/boennemann/zentodone/commit/43a53aa66262fa69b622b1c778dee96df926bc8b))


#### Features

* **sorttasks:** archive done tasks from the day before ([16f1e207](http://github.com/boennemann/zentodone/commit/16f1e207149e2b292965e8342c2094f5ae365fc9))
* **task:** don't archive done tasks of the current unit ([4cfd125d](http://github.com/boennemann/zentodone/commit/4cfd125ddad58227c9170d0fa1933f229634b631))
* **taskcell:** style for done task ([9d8edfb5](http://github.com/boennemann/zentodone/commit/9d8edfb5ad3c263f022948afcf5a69f1521b2ec0))


<a name="0.0.5-3"></a>
### 0.0.5-3 (2014-05-12)


#### Bug Fixes

* **taskcell:** subtler enter animation ([46475ea4](http://github.com/boennemann/zentodone/commit/46475ea4b88f0bab658e81cd6cbefcf5e169b674))


#### Features

* meaningful table grouped headers ([10936f43](http://github.com/boennemann/zentodone/commit/10936f43bd5da358d03e137cde02fef6bb45d016))


<a name="0.0.5-2"></a>
### 0.0.5-2 (2014-05-08)


#### Bug Fixes

* **taskcell:** slower animations are better on the eye ([35026103](http://github.com/boennemann/zentodone/commit/35026103beb8a6e83a46ba9b56856c08a2436f8e))


#### Features

* **appcache:** automatically load new app version ([ed6620a0](http://github.com/boennemann/zentodone/commit/ed6620a000c493ceda878a7ef39aa0f48bc1f418))
* **task:**
  * apply task specific styles ([cbb26190](http://github.com/boennemann/zentodone/commit/cbb26190d59a4e1e143e7c12fdb3690e17263404))
  * add actions to toolbar and handle state afterwards ([65d4fc2f](http://github.com/boennemann/zentodone/commit/65d4fc2fc906eb83028cbf98d39a58ab96e23d04))
  * type specific task screens ([5cae260c](http://github.com/boennemann/zentodone/commit/5cae260cc1e6092dd1c323980a2925a5796bed49))


<a name="0.0.5-1"></a>
### 0.0.5-1 (2014-05-08)


#### Features

* **account:** display information for better debugging and error reports ([119c5eff](http://github.com/boennemann/zentodone/commit/119c5effa36a665565ae771a99107e72c50b3495))


<a name="0.0.5-0"></a>
### 0.0.5-0 (2014-05-08)


#### Bug Fixes

* **styles:** disable android styles and dynamic type ([0bc779bc](http://github.com/boennemann/zentodone/commit/0bc779bc843c593ac05d7fc9ba46212779e9e843))
* **tasks:** return promises ([f2d65317](http://github.com/boennemann/zentodone/commit/f2d6531716dd771b62fb80379fd24754bdb78d13))


#### Features

* **taskcell:**
  * animate actions ([2fb5bfbf](http://github.com/boennemann/zentodone/commit/2fb5bfbfe9d8e4b5a88485931a37130e3989d3e3))
  * correct action colors and icons for br & mit ([ad27dde9](http://github.com/boennemann/zentodone/commit/ad27dde9e8f30f10ec817e2f8384996aeb45b328))
  * add staggered enter animation ([7e28fa11](http://github.com/boennemann/zentodone/commit/7e28fa11f68c3e5bb8bcfe02091839050f70cc03))


<a name="0.0.4-1"></a>
### 0.0.4-1 (2014-05-06)


#### Bug Fixes

* **templates:** correct paths ([c7b1952b](http://github.com/boennemann/zentodone/commit/c7b1952b68837893ccede596f6d5cd230f2ab3e4))


<a name="0.0.4-0"></a>
### 0.0.4-0 (2014-05-05)


#### Bug Fixes

* **views:** fixed width icons in navbar ([092b390e](http://github.com/boennemann/zentodone/commit/092b390ee118c7900ae140762c31b004bf4fb08e))


#### Features

* **hoodie:** react to hoodie events and update (even remote) ([e59fa4cb](http://github.com/boennemann/zentodone/commit/e59fa4cb02df5ef9b21df59827443209dbe84372))


<a name="0.0.3-1"></a>
### 0.0.3-1 (2014-05-05)


#### Bug Fixes

* **account:** fixed with for validation icons ([c2417625](http://github.com/boennemann/zentodone/commit/c2417625416377f8d860e97c7f2d5e15d50774d0))


<a name="0.0.3-0"></a>
### 0.0.3-0 (2014-05-05)


#### Features

* **manifest:** add generated manifest #offlinefirst ([0f620303](http://github.com/boennemann/zentodone/commit/0f62030375e6aaf468efde8918943b902bef1926))


<a name="0.0.2-1"></a>
### 0.0.2-1 (2014-05-05)


<a name="0.0.2"></a>
### 0.0.2 (2014-05-04)


#### Bug Fixes

* **view:** all lowercase filenames ([0eed8d57](http://github.com/boennemann/zentodone/commit/0eed8d5743fd8527ee9c0e121e42f67e61c9ac91))


#### Features

* **account:**
  * redirect to account if not logged in ([7fcbefb8](http://github.com/boennemann/zentodone/commit/7fcbefb828bf915d31eadc5ef3e34c9e77482646))
  * add styles ([65eecd86](http://github.com/boennemann/zentodone/commit/65eecd865be410b93f9c3f1b09c84bd5fac2ef91))
  * add view ([8bbc9a44](http://github.com/boennemann/zentodone/commit/8bbc9a4450bde4420cbe5309f3f5f298fd700313))
  * add controller ([d7f89fb8](http://github.com/boennemann/zentodone/commit/d7f89fb88f6c053520906c3549d40b4192532801))
  * add state ([cc56d1df](http://github.com/boennemann/zentodone/commit/cc56d1df9b3c03aecc0e5f27c8525648b9f5af24))
* **task:** hoodify/promisify ([043b8023](http://github.com/boennemann/zentodone/commit/043b802374cce8f1422385eb3402770662d7df0a))


<a name="0.0.1"></a>
### 0.0.1 (2014-05-02)


#### Bug Fixes

* **taskcell:** efficent class adding and removal ([5bd1454f](http://github.com/boennemann/zentodone/commit/5bd1454fa4f075ccfeacb39f32a1fe0206052787))


#### Features

* **br:** add br view and controller ([75341d92](http://github.com/boennemann/zentodone/commit/75341d9276a94c2fcb626aa839e9ef23f89453e1))
* **hoodie:** add hoodie.js and the angular adapter ([4354d783](http://github.com/boennemann/zentodone/commit/4354d783554701d1560bada45347c3c982aebd0d))
* **inbox:** add inbox view and controller ([f68c8593](http://github.com/boennemann/zentodone/commit/f68c8593823e790487c611798963e89e41b645f4))
* **mit:** add mit view and controller ([f545fc45](http://github.com/boennemann/zentodone/commit/f545fc458d2d9bb6978307325b65a4e10cc3f5a8))
* **sorttasks:** put taskSort logic into service ([20828ffd](http://github.com/boennemann/zentodone/commit/20828ffd35c7ab29e67b4b7164d85cffeadad3b9))
* **task:**
  * add task view and controller ([ae7a1fc8](http://github.com/boennemann/zentodone/commit/ae7a1fc8bf7a89364f28e09c2b65a3eccfc9cda8))
  * task datastructure ([2c4afe11](http://github.com/boennemann/zentodone/commit/2c4afe11e23ee873b2593270390502a25758fe18))
* **taskcell:**
  * styles ([a932af31](http://github.com/boennemann/zentodone/commit/a932af311964feacf69d764a8a25e1be9c738a22))
  * add swipeable taskcell ([a599c710](http://github.com/boennemann/zentodone/commit/a599c71050c693823afe9680ccd3f22a3ca2e074))


