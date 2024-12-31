###小饿工作室 - 跨年特别庆祝网页项目 README
##项目简介
小饿工作室 - 跨年特别庆祝 是一个专为迎接2025年到来而设计的网页项目。该网页包含了精确到秒的倒计时、烟花效果以及背景音乐，旨在为用户提供一个充满节日气氛的跨年体验。

###主要功能
##倒计时：实时显示距离2025年1月1日00:00:00的剩余时间（天、小时、分钟、秒）。
##烟花效果：使用Canvas绘制烟花动画，增添节日的喜庆氛围。
##背景音乐：提供跨年庆祝的背景音乐，用户可以通过按钮控制音乐的播放与暂停。
##响应式设计：适配不同设备的屏幕尺寸，确保在各种设备上都有良好的显示效果。
###使用技术
HTML5：构建网页结构。
CSS3：实现网页样式和动画效果。
JavaScript：实现倒计时逻辑、烟花动画以及音乐控制。
jQuery：简化DOM操作和事件处理（版本：3.6.0）。
Canvas API：绘制烟花动画。
外部文件引用
1. jQuery
来源: jQuery CDN
版本: 3.6.0
引用方式:
html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
2. 背景音乐
文件路径: background.mp3
引用方式:
html
<audio id="background-music" src="background.mp3" loop></audio>
注意: 请确保 background.mp3 文件与 index.html 文件位于同一目录下，或者根据实际路径调整 src 属性。

3. 烟花动画图片
文件路径: images/fireworks.gif
引用方式:
css
.celebration {
    background: url('images/fireworks.gif') no-repeat center center;
    background-size: cover;
}
注意: 请确保 images 文件夹中存在 fireworks.gif 文件，或者根据实际路径调整 url 属性。
