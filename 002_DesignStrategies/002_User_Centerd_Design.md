# 设计决策 二
## 以用户为中心的设计

只有在设计过程中时时站在用户的角度去考虑，才能做出最符合用户需求的产品。当你决定了你的目标用户之后，以用户为中心去考虑可以帮你更好地做出每一个设计决策。

### 了解你的用户

要了解用户，一个很有用的办法是设想一个用户在使用你的应用时各种可能的场景（译者注：这也是微信团队经常用的方法）。考虑在不同的环境下，不同的工具中，用户可能遇到的各种限制。如果条件允许，你还应该亲自到现实的环境里去体验自己的产品，看看用户在实际使用的时候对你的产品抱有什么期望。

另外，在整个设计过程中，要找到符合目标用户的人来帮忙测试你的设计原型，倾听他们的反馈，找出他们内心真正的诉求。有一点一定要牢记：开发产品要针对人和人的能力——而不是针对计算机和计算机的能力——来设计。

要知道，你作为一个开发者或者 UI 设计师，你对自己的应用的了解要远超过你的用户，你可以把这些了解用于设计更好的默认设置，更好地展示信息的方式上，但是你不要忘记你不只是忘了自己一个人而设计。你的需求不代表用户的需求，你的使用方式不代表用户的使用方式，你应该为了（潜在）用户设计，而不是为自己设计。

### 分析用户任务

在确定了目标用户之后，就可以定义和分析应用里用户可以执行的任务了。要找出这些任务相关的心智模型或概念模型，这些模型可以帮你描画出这些任务具体的表现、用户的心理预期、任务各个部分的组织形式以及完整的工作流。

要找到这些任务的心智模型，你可以想想如果没有计算机，人们是怎么完成这些事情的。在这期间会用到什么术语？有什么相关的概念、对象和手势？然后你可以根据这些相关的事物来设计，但是不要一成不变地照搬所有步骤，要利用计算机的优势，让整个流程更加简单更加流畅。

### 建立原型

根据用户任务分析得出的信息，可以做出设计初稿和原型。原型可以检验你的设计方向是否符合用户的期望。有很多种技术可以建立原型，而且有些是不需要写代码就能实现的。比如，Xcode 的 Storyboard 就是个很不错的原型工具，使用 Storyboard 可以轻易展示应用的视觉设计，还可以展示用户执行某个任务的所有步骤。你也可以用原型工具来模拟应用的特性，或者展示应用的操作方式。

### 用户测试

当原型做出来之后，你就可以找些目标用户来体验一下这些原型，观察他们的反应。如果允许的话，可以录下整个过程。观察用户行为可以帮你检验设计的效果，找到问题所在。如果产品设计和工程师有空的话，可以拉上他们一起观察用户测试，但是千万不要让他们接触到测试用户以免影响测试结果。（译者注：笑趴。）

在用户测试过程中，要确保测试范围保持在产品的关键功能上。重点关注在任务分析阶段得出的设计。在跟测试用户沟通哪些功能需要测试的时候，要确保指示的清晰完整，但是不要给出具体的使用方法，让用户根据自己的想法去做。

根据测试记录来分析设计，修正原型，然后再继续测试，看看这些修正的效果如何。你可以一直重复测试、修正、再测试，直到你觉得你的产品已经是一个合目用户需求，有用的且令人愉悦的产品。

### 关注问题解决方案，而不是功能

多数用户都是带着一个目标去使用应用的，很少有人仅仅想要浏览一遍所有的功能。为了确保你的应用可以让用户更高效，更方便地达成目标，你要保证所有的功能都能为了解决问题而紧密联系。

**避免堆积特性。**很多人喜欢往产品上添加一大堆相互间其实没什么关联的特性，就是做加法。这样很容易你的界面就会变得很臃肿，很复杂，很难用。所以每次新增一个功能的时候最好先问问自己，这个功能是不是可以帮用户更好的达成目标，如果不能，就不要加。（译者注：微信添加了大量的功能，但是很多功能是没用到的时候就不会出来，这也是控制功能膨胀的一个好办法。）

**遵守 80-20 法则。**80%的用户只会用到屈指可数的几个功能，只有 20% 会用到大部分功能。所以你应该突出强调主要功能，跟高级功能区分开。