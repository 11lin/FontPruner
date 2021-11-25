# 西山居字体精简工具
## 优势
- 只会保留指定文本的字，不会存在多余文字，精简:字体11M -> ~=1.8M
- 某些工具，精简：字体11M -> ~=3M

## 环境工具
- 需要Python Java环境
- FontCreator转换ttf格式
## 使用方式

- 汉字：src/FontExtract/ChineseOutPut.txt
- 特殊字符:src/FontExtract/unChineseOutPut.txt
  
```bash
# 精简过后的字体会输出在output目录
py FontPruner.py --inputPath=./ --inputFont=SourceHanSerifCN-Heavy.ttf --tempPath=./
```