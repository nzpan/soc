# SoC開発
- マイコン
- application processor

## マイコン
- Arm Cortex-M
- [ルネサスはAndes Technologyの32bit RISC-Vコアを採用](https://xtech.nikkei.com/atcl/nxt/news/18/08867/)                 

## application processor
linuxが動作する

MMU(Memory Management Unit)を搭載 

日本国内でapplication processorを作っているのはRenesasだけ。                                                            
### Arm Cortex-A                                                                                                        
- スマホ向け

  Qualcomm snapdragon(apple, samsung, googleは自社製品向けに内製)     
  
  MediaTek
  
- 自動車向け

  Renesas, NXP
  
- サーバー向け
                                                                                                    
  Qualcomm
  
- 特殊

  MediaTek(chromebook)
  
  Broadcom(raspberry pi)

### [SiFive RISC-V U Series](https://www.sifive.com/core-designer)

# eFlashについて
SoCに内蔵するeFlashは「CMOSロジック互換」で作成しなければならず、微細化に限界がある模様。

[リンク](https://pc.watch.impress.co.jp/docs/column/semicon/1134166.html)

28nm程度が限界でそれより先はMRAMに移行か

# 日本国内ファブについて
40nmまでのSoCまでしか作ることができず、それより微細なプロセスの場合はTSMCに頼む。
国内の設計・開発業務になにかしらの影響があるかも？

