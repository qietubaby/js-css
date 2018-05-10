<h1 aligin="center">前端性能优化</h2>

## 图片的优化
#### 1.png8/png24/png32之间的区别：

- png8 —— 256色+支持透明  8bit
- png24 —— 2^24色+支持透明 24bit
- png32 —— 2^24色+支持透明
- 访问<a href="https://tinypng.com/">png图片压缩tinypng</a>
#### 2.不同格式图片常用业务场景
- jpg有损压缩，压缩率高，不支持透明
- png支持透明，浏览器兼容号
- webp压缩程度更好，在ios webview有兼容问题。访问<a href="http://zhitu.isux.us">智图_图片压缩在线工具</a>
- svg矢量图，代码内嵌，相对较小，图片样式相对简单的场景

#### 3.CSS雪碧图
- 优点：减少网站的HTTP请求数量
- 缺点：整合图片比较大时，一次加载比较慢
-<a http://www.spritecow.com/>访问雪碧图网站spritecow</a>

#### 4.Imge inline
- 将图片的内容内嵌到html当中
- 减少网站HTTP请求数量

#### 5.使用矢量图
- 使用SVG进行矢量图的绘制
- 使用iconfont解决icon问题，访问<a href="http://www.iconfont.cn/">iconfont官网</a>

#### 6.在安卓下使用webp
<p>WebP 的优势体现在它具有更优的图像数据压缩算法，能带来更小的图片体积，而且拥有肉眼识别无差异的图像质量；同时具备了无损和有损的压缩模式、Alpha 透明以及动画的特性，在 JPEG 和 PNG 上的转化效果都非常优秀、稳定和统一。
</p>
