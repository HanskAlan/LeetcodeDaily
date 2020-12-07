# LeetcodeDaily
##动态规划：
###减绳子问题：

一段长为n米的绳子，剪成若干段，问这些剪开的绳子长度之积最大是多少?
答：dp[i]=max(dp[i],max(j*dp[i-j],(i-j)*dp[j]))
