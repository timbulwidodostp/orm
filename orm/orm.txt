# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Logistic (Proportional Odds) Ordinal Regression Model Use orm (rms) With (In) R Software
install.packages("rms")
library("rms")
orm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/orm/main/orm/orm.csv",sep = ";")
# Estimation Logistic (Proportional Odds) Ordinal Regression Model Use orm (rms) With (In) R Software
Dependen <- orm$Dependen
Independen_1 <- orm$Independen_1
Independen_2 <- orm$Independen_2
orm <- orm(Dependen ~ Independen_1 + Independen_2)
orm
# Logistic (Proportional Odds) Ordinal Regression Model Use orm (rms) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished