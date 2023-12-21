1.  时间长会掉
2. word 文档基本不好使 word不好用 是因为 java服务端 token刷新和验证有点问题
 web端调用client， 然后client携带token调用 web backend api， 但是服务端验证失败， 尽管token已经刷新了
3. excel 长时间  同上


1. 重新生成 放到文件服务器上
2. 调用这个接口 把文件拿下来并打开
3. 保存之后， 把这个文件放到服务器上面

4. 多个人 操作的化 会有一个锁的感觉

RkVJU0hVSTpVU0VSX0lORk86NDI1YjFkZWI2MDExNGNkM2EyNjJjN2MxNzU2ZjQwMTg=
RkVJU0hVSTpVU0VSX0lORk86NDI1YjFkZWI2MDExNGNkM2EyNjJjN2MxNzU2ZjQwMTg=
http://10.88.180.4:8900/api/client-control/sys/file/info

http://gitlab.myecovacs.com/eco-rc/ecovacs-fileservice.git
