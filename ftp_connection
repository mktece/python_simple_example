
from ftplib import FTP

ftp = FTP('ftp.cwi.nl')   # connect to host, default port

ftp.login()               # user anonymous, passwd anonymous@

ftp.retrlines('LIST')     # list directory contents 

import ftplib

ftp = ftplib.FTP('ftp.sunet.se', 'anonymous', 'anonymous@sunet.se')

print "File List: "

files = ftp.dir()

print files

ftp.cwd("/pub/unix") #changing to /pub/unix

FTP.connect(host[, port[, timeout]])

FTP.login([user[, passwd[, acct]]])


FTP.retrbinary(command, callback[, maxblocksize[, rest]])


FTP.retrlines(command[, callback])


FTP.dir(argument[, ...])

FTP.delete(filename)


FTP.cwd(pathname)

FTP.mkd(pathname)

FTP.pwd()


FTP.quit()


FTP.close()
