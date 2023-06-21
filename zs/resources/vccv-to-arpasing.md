# 将VCCV声库转换为ARPAsing声库

PaintedCZ的VCCV英语录音表在海外的UTAU社区十分的流行, 许多的声库和UST工程文件都支持这种录音表.  当然, 这些声库和UST工程文件也可以被转换, 使它们能够以ARPAsing的形式使用.

## 对声库进行转换

原始的VCCV英语声库可能会有"CC-", "CV_CVC"之类的子文件夹.  请将采样从子文件夹中移动至声库根目录下.  下载[这个]()索引文件并重命名为"index.csv", 并将它移动到声库根目录下.  
完成之后, 您便可以将声库文件夹拖动到Moresampler上生成OTO文件了.  但对于OTO中的重复项来说, **不要重命名, 也不要编号**.  这可能会产生上百个重复项, 它们会使ARPAsing Assistant无法正常运行.  下载[这个工具]()以便删除OTO中的重复项.  建议将参数的最大值设定在10-20之间.

## 对UST进行转换

下载并解压缩[这个插件](), 并把它放在UTAU安装目录内的Plugins文件夹中.  这个插件可以将使用Cz式发音记号的UST转换为Arpabet音素.  但这不会马上让它和ARPAsing声库完全兼容.  (比如有的音符可能会由2个以上的发音记号.)  您需要继续进行调校以便让它适合ARPAsing声库. 
原始插件由 ChieP 制作 
转换器受到 Ivory @TheIvoryShield 的启发 
插件由 KLAD 进行修改