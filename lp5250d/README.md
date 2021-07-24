# 备忘&说明


##  转PDF 源码
lp5250d\scs2pdf.c 



cat /srv/it/pdf/output1632.scs | scs2pdf > /srv/it/pdf/output1632.pdf 
‎上述示例将存储打印机状态信息‎ /tmp/pdfprintinit. ‎因此，在开始之前一定要创建此文件‎ lp5250d:
cat /srv/it/pdf/output1632.scs | scs2pdf -si /srv/it/pdf/pdfprintinit > /srv/it/pdf/output1634.pdf


http://www.chowhouse.com/~james/tn5250/ChangeLog
http://www.chowhouse.com/~james/tn5250/src/scs.h
http://www.chowhouse.com/~james/tn5250/src/scs.c
http://www.chowhouse.com/~james/tn5250/src/scs2ascii.c
http://www.chowhouse.com/~james/tn5250/src/scs2pdf.c
http://www.chowhouse.com/~james/tn5250/src/scs2ps.c



https://www.ibm.com/docs/en/zos/2.1.0?topic=guide-netspool-support-scs-code-points




lib5250\scs.c
lib5250\scs.h
lp5250d\scs2pdf.c

doc\IPDS and SCS Technical Reference.pdf


https://archive.midrange.com/linux5250/

