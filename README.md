# fullPageCV Generator
> A full page CV generator

An online demo is presented here: [CV](http://7mj59j.com1.z0.glb.clouddn.com/CV.html)

### Get started.
1. make sure [nodejs](https://nodejs.org/en/) env is installed.
2. `` git clone https://github.com/shuson/fullPageCV.git `` and run `` npm install``; this will install gulp and ectjs
3. update [example.json](https://github.com/shuson/fullPageCV/blob/master/src/example.json) file in ``./src `` directory
4. run `` gulp `` and the `` CV.html `` will be generated in `` ./dist `` directory.

### Note:
1. `` CV.html `` is not a stand-alone resource file, and it loads dependencies from CDN ``cdnjs.cloudflare.com/``.
2. please follow the [example.json](https://github.com/shuson/fullPageCV/blob/master/src/example.json) file's format, since keys are used when generating the target file.

#### MIT licenced
