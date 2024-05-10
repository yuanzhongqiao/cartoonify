<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">画这个。</font></font></h2><a id="user-content-draw-this" class="anchor" aria-label="永久链接：画这个。" href="#draw-this"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="http://danmacnish.com/2018/07/01/draw-this/" rel="nofollow"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">画画 这</font></font></em></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一款可以画卡通的宝丽来相机。你指指点点，然后射击——就会弹出一幅卡通片；相机对其所见事物的最佳诠释。该相机是用于对象识别的神经网络、Google QuickDraw 数据集、热敏打印机和树莓派的混合体。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想亲自尝试一下，</font></font><a href="https://www.kapwing.com/cartoonify" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kapwing 的工作人员已经创建了在线版本！</font></font></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/danmacnish/cartoonify/blob/master/photos/raspi-camera-cartoons.jpg"><img src="https://github.com/danmacnish/cartoonify/raw/master/photos/raspi-camera-cartoons.jpg" alt="照片" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该软件既可以在笔记本电脑等桌面环境（OSX、Linux）上运行，也可以在树莓派上的嵌入式环境上运行。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">桌面安装（仅在 OSX 和 Linux 上测试）</font></font></h3><a id="user-content-desktop-installation-only-tested-on-osx-and-linux" class="anchor" aria-label="永久链接：桌面安装（仅在 OSX 和 Linux 上测试）" href="#desktop-installation-only-tested-on-osx-and-linux"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 2.7*</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开罗（在 OSX 上</font></font><code>brew install cairo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"></font><code>pip install -r requirements_desktop.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用子目录</font><font style="vertical-align: inherit;">安装依赖项</font></font><code>cartoonify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用从命令行运行应用程序</font></font><code>python run.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当要求下载卡通数据集（~5GB）和张量流模型（~100MB）时，选择“是”。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载完成后，使用 ctrl-C 关闭应用程序。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 再次启动应用程序</font></font><code>cartoonify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统将提示您输入要处理的图像的文件路径。输入用双引号括起来的绝对文件路径。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*不幸的是，需要 python 2.7，因为正确的 python 3 轮子不适用于 pi 和桌面。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树莓派接线</font></font></h3><a id="user-content-raspberry-pi-wiring" class="anchor" aria-label="永久链接：树莓派接线" href="#raspberry-pi-wiring"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的接线图将帮助您开始使用快门按钮和状态 LED。如果软件工作正常，当 raspi 处理图像时按下快门时，状态 LED 应亮起 2-3 秒。如果指示灯一直亮着，则表明出现了问题（很可能是相机已拔出插头）。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要提示：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下图显示了 AA 电池，但这并不正确。您必须使用 eneloop 电池为相机供电 - 这些电池每个提供 1.2V 电压，以及足够的电流来驱动 raspi 和热敏打印机。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/danmacnish/cartoonify/blob/master/schematics/cartoon_camera_schematic_bb.png"><img src="/danmacnish/cartoonify/raw/master/schematics/cartoon_camera_schematic_bb.png" alt="接线图" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树莓派安装</font></font></h3><a id="user-content-raspberry-pi-installation" class="anchor" aria-label="永久链接：树莓派安装" href="#raspberry-pi-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树莓派3</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16GB SD 卡上的 rasbian 拉伸图像（8GB 太小）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">raspi 上的互联网访问</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点 + 蟒蛇</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉斯皮相机 v2</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个按钮、LED、220 欧姆电阻和面包板</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）适合 raspi 3 的热敏打印机。我</font></font><a href="https://www.adafruit.com/product/2751" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里使用了这台打印机</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请注意，您需要按照上面的接线图使用打印机 TTL 串行接口，而不是 USB。</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过运行以下命令在 raspi 上安装 docker：</font></font><code>curl -sSL https://get.docker.com | sh</code></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过以下方式设置并启用 raspi 相机</font></font><code>raspi-config</code></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从此存储库克隆源代码</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑步</font></font><code>./raspi-build.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这将下载 google Quickdraw 数据集和张量流模型，然后构建所需的 docker 映像。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑步</font></font><code>./raspi-run.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这将启动 docker 镜像。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">故障排除</font></font></h3><a id="user-content-troubleshooting" class="anchor" aria-label="永久链接：故障排除" href="#troubleshooting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查文件夹中的日志文件</font></font><code>cartoonify/logs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否有任何错误消息。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 raspi 上运行时最常见的问题是相机未正确插入。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果没有打印任何内容，请检查日志，然后检查图像是否保存到</font></font><code>cartoonify/images</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查您是否可以通过命令行从热敏打印机手动打印某些内容。</font></font></li>
</ul>
</article></div>
