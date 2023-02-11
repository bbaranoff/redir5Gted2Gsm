# redir5Gted2Gsm

```bash
git clone https://github.com/srsran/srsran
cd srsran
git checkout 254cc719a9a31f64ce0262f4ca6ab72b1803477d
wget https://raw.githubusercontent.com/bbaranoff/redir5Gted2Gsm/main/redir5Gted2Gsm.patch
patch -p0 < redir5Gted2Gsm
```
```
git clone https://github.com/bbaranoff/redir5Gted2Gsm/
cd redir5Gted2Gsm
cp *.conf /root/.config/srsran
```
Change freq mcc mnc tac
