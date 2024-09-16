# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Dynamic threshold panel data regression model Use dtp With (In) R Software
install.packages("dtp")
library("dtp")
dtp = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dtp/main/dtp/dtp.csv",sep = ";")
# Estimation Dynamic threshold panel data regression model Use dtp With (In) R Software
dtp<-dtp(GDPPC ~ FDI+OPEN|INF|INF,dtp,index=c("pays","ann"),4,2,0.95,0.8,1,graph = TRUE)
summary(dtp)
# Dynamic threshold panel data regression model Use dtp With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished