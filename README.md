# newestVersion
这个文件包含了我修改好的所有代码（不是最终版本），可以在本地通过npm运行在localhost上。
目前问题：Github pages Deploy 出来只有README。
对应关系：原作者 https://github.com/poloclub/cnn-explainer/tree/master/src/detail-view 有三个branch（master，dev，gh-pages），dev没用，删了无影响。我的master branch对应原作者的master branch，原作者用gh-pages branch作为github pages的source可以跑出页面。（我不知道他这个branch哪来的）

我之前把原作者的gh-pages下下来，传为我改好的新branch，在bundle.css.map里改了好多它引用的网站——从“https://github.com/poloclub/cnn-explainer” 改成了 “https://github.com/kikimasu1/cnn-explainer” ，后来deploy它可以抛出结果（但是图片access不到）结果链接：https://kikimasu1.github.io/testo/ 

希望大家给个解决方法 谢啦。

可以研究下原作者的gh-pages branch
