# JDC-2.8测试
//查看原程序PID,第一行第二列为程序的PID
ps -ajx|grep JDC
//结束程序（*****改为你的PID，本文为24303）
kill -9 *****

  rm -rf JDC
  Finalshell 拖入root
  chmod 777 JDC

  ./JDC

  nohup ./JDC &