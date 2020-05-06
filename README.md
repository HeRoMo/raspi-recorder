# Setup Raspberry Pi for TV Recorder

This is an Ansible playbook to setup Raspberry Pi for TV recorder.

## Requirement

- Raspberry Pi 4 (maybe Raspi3 is ok, but I did not try it.) with Raspedian Lite
- Plex [PX-Q1UD](http://www.plex-net.co.jp/product/px-q1ud/)
- B-CAS Card (see https://www.b-cas.co.jp/cardorder/view/order/agreement.html)
- E-Card Reader

## Run Playbook

```bash
> ansible-playbook -i hosts site.yml --private-key <ssh private key>
```

## Using OSS Products
- [stz2012/libarib25: Linux用ARIB STD\-B25ライブラリ（各録画ツールにarib25ソースを添付しなくとも、Makefile内で\-larib25でコンパイルできる）](https://github.com/stz2012/libarib25)
- [Chinachu/Mirakurun: A Modern DTV Tuner Server Service for ISDB\.](https://github.com/Chinachu/Mirakurun)
- [Chinachu/Chinachu: Most Lovely DVR Software in Japan\.](https://github.com/Chinachu/Chinachu)
