# plot-for-abstract
##logistic regression plot 

```
 x=df$V1
 y=df$V2
 plot(x,y,xlab='number of phenotypes',ylab='AUC',main='logistic regression performance')
 smoothingSpline = smooth.spline(x, y, spar=0.6)
 lines(smoothingSpline,col='red',lwd=2)
 abline(0.6266,0,col='blue',lwd=2)
 legend('bottomright', legend=c('NTF preprocessed features','raw_features'),lty=c(1,1), lwd=c(2,2),col=c('red','blue'))
 ```
