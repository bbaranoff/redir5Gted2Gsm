# redir5Gted2Gsm

```bash
git clone https://github.com/srsran/srsran
cd srsran
cp *.conf /root/.config/srsran
```
Change freq mcc mnc tac
```
git checkout 254cc719a9a31f64ce0262f4ca6ab72b1803477d
wget https://raw.githubusercontent.com/bbaranoff/redir5Gted2Gsm/main/redir5Gted2Gsm.patch
patch -p0 < redir5Gted2Gsm
```
