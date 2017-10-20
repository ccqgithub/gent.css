## 响应式断点设置

> 移动端优先

```less
// mobile first
@media-sm: ~"(min-width: 361px)";
@media-md: ~"(min-width: 769px)";
@media-lg: ~"(min-width: 1025px)";
@media-xl: ~"(min-width: 1281px)";
```

> 严格模式

```less
// strict range
@media-strict-sm: ~"(min-width: 360px) && (max-width: 768px)";
@media-strict-md: ~"(min-width: 769px) && (max-width: 1024px)";
@media-strict-lg: ~"(min-width: 1025px) && (max-width: 1280px)";
```

> PC端优先

```less
// mobile first reverse: pc first
@media-reverse-xs: ~"(max-width: 360px)";
@media-reverse-sm: ~"(max-width: 768px)";
@media-reverse-md: ~"(max-width: 1024px)";
@media-reverse-lg: ~"(max-width: 1280px)";
```
