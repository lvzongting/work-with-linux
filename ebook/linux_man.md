linux生存手册
==============

对linux下有哪些好用的应用程序是各位最关心的实质问题，所以先来完善这个问题，在邮件列表上这些问题也是经常被提及的。附录中是王垠先生原文中的内容，留在附录供各位文档贡献者参考。

这一部分分为四个字部分：

- GUI 现在linux下的图形程序已经得到了长足的发展
- CLI 在framebuffer流行的情况下命令行工具也得到了前所未有的发展，fb是大家非常怀念的DOS中硬写屏技术在linux下的再现。
- 其他系统下使用GNU软件堆栈 GNU软件堆栈由于其开源的特性可以被移植到各种地方，即使并不适用linux作为内核，这足以说明开源强大的生命力。
- linux内核 linux内核以其优秀的性能，优秀的移植性以及强大的一致性(兼容性)被移植到各种有意思的设备上。


GUI图形界面程序
--------------

**日常应用**

- 浏览器
- PDF阅读器
- 英汉词典部分 goldendict 也非常强大.
- gui方面比较方便的终端guake ,主要是呼出有点像cs的控制台.
- 编辑器非自由的话还有sublime text,还有一个开源go语言的实现,
- qq的话webqq也是一种方式.
- ZeroBrane Studio 轻量级lua ide.
- 图形编辑Krita(Digital Painting for Artists) 有点ps的感觉.比较重量级.qt
- eclipse +各种插件.几乎所有类型的语言都有.用过c++和lua的.avr也还不错.比较重量级,扩展性较好
- shutter 增强的截屏软件,有一些简单实用的编辑功能.
- meld,图形化的diff工具.比较美观易用.
- diffpdf,pdfdiff工具,比较少有的需求.查看一些只有pdf格式的标准文件的变化比较实用,比如两个不同年份的标准,到底修改了什么内容.
- vlc视频播放器,多种格式.比较大
- 游戏 steam游戏平台.一些比较前沿的(独立)游戏发布
- 虚拟化,virtualbox
- wireshark 网络抓包,学习网络知识,调试网络程序等,命令行tcpdump. netcat网络程序调试


**性能测试**

- Phoronix text suit

**本地化**

  *由于经济、社会发展的因素，linux的本地化起步的比较晚，但是发展的速度非常快。由于早先贸易制裁的原因，我们无法用上先进的电子设备，所以我们的计算机事业起步的比较晚，而且起点低，早先时候我们只能用上性能低下的个人计算机能接触到的作业系统只有DOS，这个年代linux还尚未出现，Unix不卖给我们。后来，随着M$推出windows，并推出NT内核以后，我们就惯性的用起来windows，我们在计算机教育事业上的投入非常有限，所以在本科之前并没有一份好的教材。M$就趁着这个薄弱环节抢占了我们的第一印象。可以这么说，我们的计算机教育，其实就是M$的培训。*

  *随着互联网的兴起，我们有机会通过互联网去了解外面的世界，在网络中先进的受过高等教育的认识，开始意识到Linux的优势和流行程度，开始着手将先进的操作系统引入国内。并且，随着我们外交上的胜利，我们也引入了一大批优秀的计算机教育方面的教材(比如恐龙书)，这些教材都以Linux/Unix为对象进行教学。但是，时至今日，我们的本科以前的计算机教育仍然没有得到广泛的关注。中科院和龙芯正在努力改变这个现状，在江苏进行试点，很快将推广至全国。*
  
  *linux本地化还不是很好的情况下，这里专门开辟出一个部分来帮助大家在本地使用linux。*
   
- QQ

  pidgin-lwqq

- 迅雷

  axel + 百度网盘



**商业壁垒**

   *由于linux是分享代码，并不直接参与商业，但是其优秀的性能给很多人带来了压力，所以很不幸一些商业壁垒也确实存在。*
   
- NTFS

  NTFS这个都不能算作文件系统的东西，给很多普通用户带来了诸多不便，可以说任何一个成熟的操作系统都不会支持它。但是，有些人会拿这个说事。比如一个无辜的老太太用一个NTFS格式的移动硬盘放到Mac OSX上，结果不支持，所以来指责Linux做的太差了。如上这个事件叫做“瓦莱丽门”事件，是M$通过一个可怜被骗的老太太，来要挟其他操作系统支持NTFS格式，可是反过来，又在技术上制造壁垒。
   
  不过我们有NFTS-3g项目
  
- Office

  办公室的白领又是另外一个被绑架的对象，这些人没有Office就会下岗。
  
  libreoffice  或是google doc都是一个好的解决方案，可能有人会抱怨对原来文档的格式支持不好，其实，当你用不同版本的office的时候也会出现这个问题。你就把这些当做一个不同的office版本吧。


CLI命令行界面程序
--------------

**常用应用**
    
- 终端复用 tmux
- 一个比较现代的shell(相对bash而言):fish,有些惊艳的功能.
- webfs 专一的轻量级的web文件系统实现.也不失为一种文件分享的方式.





GNU软件堆栈
--------------
**Mac OSX 系统**

- Gentoo Prefix
- HomeBrew
- Fink
- MacPorts

**Android 系统**

- Archlinux ARM
- Debian on Android

**Chrome OS 系统**

- Gentoo
- Gentoo Prefix
- Archlinux

**windows 系统**

*对于windows系统的问题，我不知道应该不应该写，有好有坏吧，先预留在这里。*

- Cygwin
- Cygwin Ports


Linux内核
--------------





附录
--------------

Shell: bash。它结合了 csh 和 ksh 的优点，并且有 readline 功能，你可以随意绑定自己的键盘。

编辑器： VIM, Emacs。

程序开发： GCC, make, ld, Scheme48, j2sdk, Perl, Python, Tcl/Tk ...

论文，幻灯工具：LaTeX, ConTeXt

绘图工具：MetaPost。这个语言太强了，以至于我只用它了。你不熟悉的话可以用 xfig, dia 来画一些流程图之类的图片。

图像处理：ImageMagick。其中的 import 程序可以屏幕抓图，convert 程序可以转换图像格式，display 可以显示图片和简单编辑(缩放，换质量，转格式，简单绘图，简单虑镜)。通常我就这么点需要。如果你要更强大的图像工具可以用 Gimp, 它几乎和 Photoshop 差不多。

自动管理工具：make。我可以用make来自动编译程序，自动编译文档，自动更新插图…… 全自动，而且不会重复劳动。

数值计算程序：SciLab。这个程序基本上可以代替 Matlab。

代数计算程序：MAXIMA。这个程序基于世界上最老的计算机代数系统之一: 由美国能源部(DOE)发行的 MIT Macsyma 系统。它是用 Common Lisp 实现的。很多现在的符号计算程序比如 Maple 都从 MAXIMA 身上学到很多东西。它现在经过 DOE 批准以GPL发行，永远是一个自由软件。

加密程序：GnuPG。我的 PGP 密钥就是它搞出来的。

打包，压缩程序。什么都有: tar, gzip, bzip2, zip, rar, ...

虚拟光驱程序。Linux 不需要虚拟光驱程序，直接 mount 就行了。

ftp 服务器：proftpd, vsftpd。proftpd 功能很强，但是我只用了最简单的一种设置。

WWW 服务器：apache。(我一般没有开)

ftp 客户程序：lftp，ncftp。它们都是文本方式操作的，但是比起图形界面的方便的多。比如 lftp 几乎具有 bash 的所有方便功能，Tab 补全，bookmark, queue, 后台下载，镜像…… Linux 也有图形界面的 ftp 客户程序，但是大多不稳定，有很多问题。这就是很多人抱怨 Linux 不如 Windows 的一个小原因。还有很多人用 Wine 模拟 Windows 的 leapftp，其实 lftp 比 leapftp 好很多，你需要的只是适应一下。

自动下载工具：wget。它非常稳定，有一次我下载一个程序，用 IE 和 Mozilla 下载回来的文件都是坏的，最后还是 wget 可靠的传输了数据。用它甚至可以镜像整个网站，比起 WebZip 这样的 Windows 程序强多了，而且不会因为你不付钱就在下载回来的网页里强制插入广告。

虚拟终端：rxvt, xterm, gnome-terminal, mlterm, ...

X server: XFree86

窗口管理器：FVWM。编译加入了 libstroke。

中文输入：XSIM。被我修改过以适应 FVWM 的需要。另外推荐你还可以用 SCIM。

email 处理：Mutt + Postfix + fetchmail

看 PDF, PS, DJVU 文件：Acrobat Reader, xpdf, GhostScript, gv, djvu工具包和 netscape 插件。

看CAJ文档。我从来不看CAJ之类的文档，如果找不到PDF或PS，直接去图书馆借最好。

看网页：Mozilla, Phoenix, lynx。Mozilla-Xft 的显示效果比 IE 好很多。

英汉字典：IBM智能词典，星际译王。

编辑网页：我用 VIM 直接写 HTML。你如果想要图形方式的可以用其它的比如 screem, BlueFish。

登录其它 UNIX, Linux 机器：openSSH, telnet。 我喜欢用 openSSH 把其它机器的 X 程序通过 ssh 加密的隧道传到我机器上显示。

登录 Windows2000 server 的 display service: rdesktop，...我有一天试了一下，不错。后来就没有用过了。

同步程序：rsync。我用 rsync 通过 ssh 来跟某些机器同步数据，或者做自己机器上不同目录间的同步。

上BBS：rxvt(或任何一种终端) + telnet + chatbot(helloooo 机器人的程序)

QQ, ICQ: 我没有 QQ 或 ICQ。不过你可以用 Gaim, 它同时支持 QQ, ICQ 和很多其它的即时通信方式。ICQ 用户也可以用 Licq。

放录像：MPlayer, RealPlayer。MPlayer 太好了，直接就可以放 VCD, DVD, divx, wma, wmv ... 用 Windows 的同学都很羡慕我，说 Windows 要放这个需要大堆插件。rm 最好还是用 realplayer 放，它也是免费的。

放音乐： xmms(mp3,ogg都可以), mpg321(放mp3), ogg123(放ogg)。mpg321 不如 xmms 管理音乐文件那么方便，但是有时我还是用 mpg321 放 mp3 作为背景音乐，因为懒得开一个xmms窗口

游戏：我觉得 KDE 的那个 ksokoban(推箱子)，很好玩

看 Word 文档。请 Word 用户把文档全部转为 PDF 或 PS 再给我，文档里没有特殊的格式干脆就用文本吧，何必那么麻烦。以前很奇怪的是，通知里本来没有什么特殊的格式居然还要发doc附件的email。现在好了，我们系发通知都用文本，PDF，甚至图片了

其它程序：还有很多我需要用而你不一定用得着的。比如，Doctor Scheme, Scheme48, Scsh, kawa...这些程序只有 Doctor Scheme 有Windows版本。还有很多幕后工作但是你一般不察觉的：xinetd, telnetd, sshd, crond, atd, lpd, ... 他们都比 Windows 的对应者强的多，或者根本没有对应者。 
