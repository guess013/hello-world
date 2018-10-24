# hello-world
# This code finds out the average, variance and standard deviation of 5 values

start
int v1,v2,v3,v4,v5;
float avg=0.00;
float diff=0.00;
float var=0.00;
float std_dev=0.00;
float sum=0.0;

sum=(v1+v2+v3+v4+v5);

avg=sum/5;

diff1 = v1-avg;
diff2 = v2-avg;
diff3 = v3-avg;
diff4 = v4-avg;
diff5 = v5-avg;

var={(diff1)^2 + (diff2)^2 + (diff3)^2 + (diff4)^2 + (diff5)^2}/5;

std_dev = (var)^0.5;
end




