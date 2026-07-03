# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Delete-d Jackknife Estimate for Linear Regression Use jackknife.lm (jackknifeR) With (In) R Software
install.packages("jackknifeR")
library("jackknifeR")
# Estimation Delete-d Jackknife Estimate for Linear Regression Use jackknife.lm (jackknifeR) With (In) R Software
jackknife.lm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/jackknife.lm/main/jackknife.lm/jackknife.lm.csv",sep = ";")
jackknife.lm <- jackknife.lm(jackknife.lm ~ jackknife.lm_1 + jackknife.lm_2 + jackknife.lm_3, d = 2, data = jackknife.lm, numCores = 2)
summary(jackknife.lm)
# Delete-d Jackknife Estimate for Linear Regression Use jackknife.lm (jackknifeR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished