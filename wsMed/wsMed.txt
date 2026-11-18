# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# structural equation model (SEM) for analyze two-condition within-subject mediation Use wsMed With (In) R Software
install.packages("wsMed")
library("wsMed")
# Estimate structural equation model (SEM) for analyze two-condition within-subject mediation Use wsMed With (In) R Software
wsMed = read.csv("https://raw.githubusercontent.com/timbulwidodostp/wsMed/main/wsMed/wsMed.csv",sep = ";")
wsMed <- wsMed(data = wsMed, M_C1 = c("A1", "B1"), M_C2 = c("A2", "B2"), Y_C1 = "D1", Y_C2 = "D2")
summary(wsMed)
# structural equation model (SEM) for analyze two-condition within-subject mediation Use wsMed With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished