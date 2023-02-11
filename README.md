# redir5Gted2Gsm

git clone https://github.com/srsran/srsran
cd srsran
git checkout 254cc719a9a31f64ce0262f4ca6ab72b1803477d
wget https://raw.githubusercontent.com/bbaranoff/redir5Gted2Gsm/main/redir5Gted2Gsm.patch?token=GHSAT0AAAAAAB6LMKHOYRN5AGOK5AR5CL6AY7IBGVA
patch -p0 < redir5Gted2Gsm
