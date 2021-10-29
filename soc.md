# SoC開発
- マイコン
- application processor

## マイコン
- Arm Cortex-M、NVIC(Nested Vectored Interrupt Controller)
- [ルネサスはAndes Technologyの32bit RISC-Vコアを採用](https://xtech.nikkei.com/atcl/nxt/news/18/08867/)                 

## application processor
- Arm Cortex-A、GIC (General Interrupt Controller) 
- linuxが動作する
- MMU(Memory Management Unit)を搭載 
- 日本国内でapplication processorを作っているのはRenesasだけ。                                                            
### 製造メーカー                                                                                                        
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

[link](https://pc.watch.impress.co.jp/docs/column/semicon/1134166.html)

28nm程度が限界でそれより先はMRAMに移行か

# MRAM
Magnetoresistive Random Access Memory, 磁気抵抗メモリ

[Samsung/IBM/TSMC/GFがMRAM開発の最新成果を披露](https://pc.watch.impress.co.jp/docs/column/semicon/1297554.html)

[米国のルネサスが販売している8MビットのSTT-MRAM](https://eetimes.itmedia.co.jp/ee/articles/2104/23/news028.html)

# 車載SoCを取り巻く状況について

[TOYOTA Arene OS](https://car.watch.impress.co.jp/docs/news/1303287.html)

スマホ用SoCと車載SoCの大きな違いはリアルタイム性。

リアルタイム性を考慮したOSになっていくのでは？

# 日本国内ファブについて
日本国内では40nmまでのSoCまでしか作ることができず、それより微細なプロセスの場合はTSMCに頼む。

国内の設計・開発業務になにかしらの影響があるかも？



