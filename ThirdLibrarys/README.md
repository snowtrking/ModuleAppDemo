**ThirdLibrarys** 文件夹里用来放一些第三方库的 **Module** (某些三方库没有提供远程依赖，或者有些时候需要修改某些三方库源码，
这时就需要直接依赖 **Module** 里的源码)，然后在 **settings.gradle** 中加入 **':ThirdLibrarys:[三方库 Module 名]'**，
 即可在 **build.gradle** 中依赖