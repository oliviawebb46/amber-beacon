# amber-beacon

Cloud engineer · Kubernetes and Terraform · archiving old docs

日常脚本的集中地

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/amber-beacon.git
cd amber-beacon
cargo build --release
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
