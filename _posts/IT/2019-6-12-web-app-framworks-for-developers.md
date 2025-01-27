---
title: "web app开发框架"
date: 2019-6-12
description: 
categories:
  - IT
tags:
  - Social Media
  - Remote Jobs
  - Internet
  - Math & CS
  - AI
---

适合于初級开发者的日常需求

# 优质web app方案的关键因素

关键因素：

1. 优质的搜索功能
2. 內容管理系统（CMS）
3. 多语言系统
4. 移动端支持
5. 商业智能和数据分析
6. 管理多种渠道的功能
7. 有可视化界面（GUI）的后台管理
8. 可支持的第三方插件
9. 开发文档，使用说明，测试环境
10. 网络和数据安全性

### 优质的搜索功能

这在市场上扮演非常重要角色的功能之一，有助于提高转化率。基本上，此功能是一种过滤功能，可处理关键字并帮助您在搜索和销售中获得准确的效果。

### **內容管理系统（CMS）**

内容（比如各种软文，产品概念，相关文创内容等）是使网站在全球市场中独树一帜的系统。这是对网站产生巨大影响的功能之一，它是提高转化率的关键。

### 多语言系统

Multiple language CMS web app

对多种语言的集中管理，而不是每个语言都需要维护一份代码。

### 移动端支持

每个人都希望能够在移动设备上轻松浏览，甚至考虑小程序，并将维护成本降到最低。最起码应采取响应式和自适应式的设计，在页面功能和美学的设计上都应采用移动端用户（小屏幕设备）体验优先的的设计。当前的网站设计（几乎没有响应式设计和自适应式的设计，几乎没有移动端优先的考虑）对移动端用户是非常不友好的。

### BI 商业智能

数据驱动业务。在管理数据时，必须获取有关数据的准确详细信息。在管理数据时应保持速度，商业智能有助于在网站上完成任务，因为只有通过速度和流程，您才能分析交易的深度，抓住商业机会。

### 管理多种渠道的功能

同时管理多种渠道的产品，列表和订单的功能，除了在自己的品牌网站售卖，可能还在其他平台上售卖，考虑初始阶段可能需要通过电商巨头平台的导流。

### 有可视化界面（GUI）的后台管理

可视化的内容管理界面是降低维护成本的关键因素，离开了程序员和就无法完成日常维护的设计是非常不完善的，必须是普通人不用教也可以管理的后台。

### 可支持的第三方插件

第三方插件旨在提供适应性，定制性和创新性。这些功能可以在开发网站时使用，某些功能可能不是标准软件包的一部分，便需要通过第三方插件实现。

上述的许多功能便是可以通过插件实现的，比如: 多语言系统，可视化系统管理后台，内容管理后台等。当前框架安装了哪些插件？找到对应的CMS版本，才能安装翻译和SEO等其他插件plugin 。

### 开发文档，使用说明，测试环境

产品和内容是业务的核心，网站就像外装、房子、交通工具，修饰、陈列或装载核心。

服装随着时间推移需要更换，房子和交通工具需要在技术迭代过程中可以同步得到修缮和升级，完善的开发文档是维护网站稳定运行的保障，无论开发人员如何更换，网站都可以得到应有的维护。

使用说明可以帮助企业内部成员更高效地使用网站和协作办公。

在商业环境中，尤其是自建网站，除了正在直接使用的网站（生产环境），通常还需要一个备份网站（测试环境）。

### 安全性

AAA (Authentication, Authorization, Account) 原则，不同的角色（开发人员，数据管理，运维，测试，管理层等...）需要有明确的权限，并根据权限设置账号功能，操作记录可跟踪。

有灾难备份方案。


# 主流框架和语言

## [软件框架](https://en.wikipedia.org/wiki/Software_framework)

框架的功能类似于基础设施，与具体的软件应用无关，但是提供并实现最为基础的软件架构和体系。

[软件开发者](https://zh.wikipedia.org/wiki/%E8%BB%9F%E9%AB%94%E9%96%8B%E7%99%BC%E8%80%85)

通常依据特定的框架实现更为复杂的运用和业务逻辑。这样的软件应用可以在支持同一种框架的软件系统中运行。

Tips：

由于没有开放互联网，不能使用更新的服务器镜像并获取高级版本的编程框架，国内软件版本相较落后，这是先天条件决定的，如果决定做国际业务，请考虑用国际网络资源。

软件框架和编程语言的主流类型选择如下。

## Media framework 媒体平台

Most simple way 

## [GitHub pages](http://pages.GitHub.com)

for: personal website, blog, profile, CV, gitbook style, side categories etc.   

[Github-jekyll-theme](https://github.com/topics/jekyll-theme)

[jekyll-minimal-mistakes/](https://mmistakes.github.io/minimal-mistakes/)

[jekyll-gitbook](https://github.com/sighingnow/jekyll-gitbook)

**以下框架适合做主站页面，唯一缺陷是没有多语版**

https://just-the-docs.com/

https://kitian616.github.io/jekyll-TeXt-theme/ 

https://mazhuang.org/

多语版个人主页

[https://george-gca.github.io/multi-language-al-folio/](https://george-gca.github.io/multi-language-al-folio/)

# Hugo

找到一些比较好的主题，全部都要多语版。

https://themes.gohugo.io/themes/hugo-book/

类似gitbook简约的书或文档风格

https://themes.gohugo.io/themes/up-business-theme/

适合商业和非营利组织的主站

### Notion + Super.so

[Super.so](https://super.so/)

**Priority:**

Notion: easy CMS, wiki, project management, online co-working platform, blog, web app, etc.

Super.so: custom domains, rich 3 party tools, friendly SEO

[https://www.indiehackers.com/post/why-we-rebuilt-our-website-entirely-in-notion-cac14af8aa](https://www.indiehackers.com/post/why-we-rebuilt-our-website-entirely-in-notion-cac14af8aa)

Multiple language page issues

[https://community.super.so/c/questions/can-create-multiple-languages-of-web-app-by-notion](https://community.super.so/c/questions/can-create-multiple-languages-of-web-app-by-notion)

[https://www.progress.com/sitefinity-cms/platform/multilingual-websites](https://www.progress.com/sitefinity-cms/platform/multilingual-websites)

Pro: 每月付费12美金

如果不在乎网站前端模板的傻瓜化调用，

notion+fruition免费搭建自定义域名主页

[https://the-block.club/Fruition-Notion-e05ddf4392744a8a819a30ac7952520b](https://the-block.club/Fruition-Notion-e05ddf4392744a8a819a30ac7952520b)

[https://blog.skylershu.com/post/fruition](https://blog.skylershu.com/post/fruition)

Notion暂不支持域名自定义，但是通过cloudflare的域名改写，可以实现独立域名访问notion

[https://sspai.com/post/58441](https://sspai.com/post/58441)

将Notion同步备份到Github上

[https://blog.csdn.net/qq_39555106/article/details/126047247](https://blog.csdn.net/qq_39555106/article/details/126047247)

备份到Gitlab上

[https://github.com/darobin/notion-backup](https://github.com/darobin/notion-backup)

短域名 [Bit.ly](http://bit.ly) 

Today I create short URL by bitly, I don't use private domain, although I have and it's cheap enought, but I don't want to maintain it anymore.

之前的博客，懒得搬家了，就保留在原地。gitbook也好用，但是还没有notion这么灵活。

[https://atom-x.gitbook.io/li-blog/](https://atom-x.gitbook.io/li-blog/)

## Edu framework 教育平台

课程管理平台可以自建或托管，学习管理系统 LMS，开发框架，例如:

第一级，始祖版： 经过20-30年，最早由科研和大学开始研发和使用，最接近教育的本质，大多数开源了，从外观看比较老土，或者犹如老版本的ERP，需要较好教育程度的专业人士使用，例如。

Blackboard, Moodle, Sakai, Desire2Learn, Canvas (certified partner), Jenzabar, Angel, and more.

第二级，专业版：逐渐商业化，但是很多免费的顶级大学课程，算是半公益，类似NGO，从外观看比较中规中矩，或者犹如大学内部管理系统，需要受过一定教育的半专业人士使用，类似coursera。

[Piazza](https://piazza.com/)

第三级，商业版：完全商业化，接近电商公司的营销套路特别多，从外观看特别花哨，功能很傻瓜化，适合普及给大多数人用，例如。

[https://kajabi.com](https://kajabi.com/)

[https://teachable.com](https://teachable.com/)

海外版小鹅通

## Ecommerce framework 电商平台

[CodeIgniter (PHP)](https://codeigniter.com/)

[Laravel (PHP)](https://laravel.com/)

[Ruby on Rails (Ruby)](https://rubyonrails.org/)

[Django (Python)](https://www.djangoproject.com/)

[Angular (JavaScript)](https://angular.io/)

## 热度比较

根据google trends对全球应用框架的监测，laravel是更受欢迎，在未来继续有潜力的框架，更流行的框架有更活跃的社区和支持，codeigniter 不是很好的选择。

### Laravel框架案例

[选择Laravel的详细理由](https://www.cloudways.com/blog/laravel-ecommerce/)

使用Laravel的框架CMS

[https://demo.bagisto.com/bagisto-34-92-8-44/](https://demo.bagisto.com/bagisto-34-92-8-44/)

电商店铺展示

[http://allspot.store/](http://allspot.store/)

如果要更高效率，低成本，快速实现目标和理想效果，相比Laravel，还有更便捷的方式，不要自建，而是选择托管方案。

## 域名注册

[免费的域名申请](https://nic.eu.org/)

[Namesilo](https://www.namesilo.com/)

Namecheap 



## 自定义域名邮箱

使用 Cloudflare 配置个性域名邮箱，通过gmail代理收发邮件

[https://blog.shuziyimin.org/1355](https://blog.shuziyimin.org/1355)
注意事项：应用专属密码可重复使用，但无法保留和再查看，可以重复申请多个。

居然绕过了google workspace注册付费，也能使用gmail做收发代理，但是立即收到了google workspace的催促注册邮件，😂，看看能挂多久吧。

[用QQ企业邮箱打造自己的个性域名邮箱](https://cloud.tencent.com/developer/article/1344989)

# 托管服务方案

## **电商三大类型平台对比**

1. 托管服務（完全依附）：使用amazon, alibaba 等monopoly giant 垄断巨头的完全托管，不需要任何技术人员；
2. 托管平台（相对独立）：使用shopify, woocommerce 等 service provider 新兴服务商的技术服务，不需要任何技术人员；
3. 自建平台（完全独立）：使用codeigniter, laravel 等技术框架 self built completely 完全自主建造，需要聘用程序员或外包公司写代码，需要长期的技术支持和运营维护；

[programming framework selection](https://quip.com/TBrwAKmOSb8X)

## **分析结论**

经过对当前taiaochi公司情况和业务需求的分析，作为IT开发者，我们推荐使用第二种方案“托管平台”，适合于商户类型为高中级用户，大品牌，有稳固的客流，较好的运营团队。例如采纳shopify，能够相对更高效率，低成本达成理想目标。

[https://www.shopify.com/](https://www.shopify.com/)

自建平台vs.托管平台vs.托管服务，主要差别为是否自己自主掌握技术开发，市场营销，美术，文案，活动等等是无论任何一种类型商业都少不了的。当然藉助于讬管平台，可以最大化地外包服务，减少商户的人力投入。

## 参考资料

**E-commerce for Codeigniter**

Udemy教学：在CI中做电商网站

[https://www.udemy.com/course/e-commerce-in-codeigniter-step-by-step-guide-from-scratch/](https://www.udemy.com/course/e-commerce-in-codeigniter-step-by-step-guide-from-scratch/)

没太搞清楚，需要用什么框架模板搭建。

适用于CI的电商框架如下

- [Shopify](https://themeforest.net/category/ecommerce/shopify?tags=ecommerce,responsive&term=ecommerce%20codeigniter#content)
- [OpenCart](https://themeforest.net/category/ecommerce/opencart?tags=ecommerce,responsive&term=ecommerce%20codeigniter#content)
- [PrestaShop](https://themeforest.net/category/ecommerce/prestashop?tags=ecommerce,responsive&term=ecommerce%20codeigniter#content)
- [Magento](https://themeforest.net/category/ecommerce/magento?tags=ecommerce,responsive&term=ecommerce%20codeigniter#content)

Magento is an open source platform

[https://www.quora.com/Is-CodeIgniter-able-to-develop-an-e-commerce-website](https://www.quora.com/Is-CodeIgniter-able-to-develop-an-e-commerce-website)

Bootsrap

[https://github.com/kirilkirkov/Ecommerce-CodeIgniter-Bootstrap](https://github.com/kirilkirkov/Ecommerce-CodeIgniter-Bootstrap)

在CI中集成wordpress

integrate Wordpress into Codeigniter

[https://www.quora.com/Is-it-possible-to-integrate-WordPress-into-CodeIgniter](https://www.quora.com/Is-it-possible-to-integrate-WordPress-into-CodeIgniter)

---

## 媒体创作站需求分析

1. 多地自动备份
为了防备触发网络审查的敏感词而被删或屏蔽，需要在多个平台备份，
例如在Notion上创建主站和写作，同时备份到github、gitbook和google drive。
2. 分享权限范围设定
部分文章和内容必须在限定范围分享，
例如仅限注册和付费会员可查阅或可编辑，其他内容可面向普通公众。
