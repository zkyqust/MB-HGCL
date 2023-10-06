# MB-HGCL
##run the codes
### Taobao
``` bash
python MBSSL.py --dataset Taobao --wid [0.01,0.01,0.01] --coefficient [1.0/6,4.0/6,1.0/6] --decay 0.01 --batch_size 256 --ssl_temp 0.2
### Beibei
``` bash
python MBSSL.py --dataset Beibei --wid [0.1,0.1,0.1] --coefficient [0.0/6,5.0/6,1.0/6] --decay 10 --batch_size 256 --ssl_temp 0.2
