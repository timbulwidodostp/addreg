# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Additive Regression for Discrete Data Use addreg With (In) R Software
install.packages("addreg")
library("addreg")
addreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/addreg/main/addreg/addreg.csv",sep = ";")
# Estimation Additive Regression for Discrete Data Use addreg With (In) R Software
addreg <- addreg(Satellites ~ Width + Dark + GoodSpine, data = addreg, family = poisson)
summary(addreg)
# Additive Regression for Discrete Data Use addreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished