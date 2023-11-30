you are expected to know what you are doing.

copy the arm64 config from `configs` dir to `.config`, fire off make. enjoy. 


note: this was a bit of a pain to get working so if you run into trouble don't worry 



```
$ file busybox_unstripped
busybox_unstripped: Mach-O 64-bit executable arm64

$ ./busybox_unstripped
BusyBox v1.20.0.git (2023-11-29 17:34:09 PST) multi-call binary.
Copyright (C) 1998-2011 Erik Andersen, Rob Landley, Denys Vlasenko
and others. Licensed under GPLv2.
See source distribution for full notice.

Usage: busybox [function] [arguments]...
   or: busybox --list[-full]
   or: function [arguments]...

	BusyBox is a multi-call binary that combines many common Unix
	utilities into a single executable.  Most people will create a
	link to busybox for each function they wish to use and BusyBox
	will act like whatever it was invoked as.

Currently defined functions:
	[, [[, ar, ash, awk, base64, basename, bbconfig, bunzip2, bzcat, bzip2, cat, catv, chgrp, chmod, chown, chpst, chroot, cksum, clear, cmp, comm, cp,
	cpio, cryptpw, cttyhack, cut, date, dc, dd, diff, dirname, dnsdomainname, dos2unix, dpkg, dpkg-deb, du, echo, ed, egrep, env, envdir, expand, expr,
	fakeidentd, false, fgrep, find, flock, fold, fsync, ftpd, ftpget, ftpput, getopt, getty, grep, gunzip, gzip, hd, head, hexdump, hostid, hostname, id,
	inetd, ipcalc, kill, less, ln, logger, login, logname, ls, lzcat, lzma, lzop, lzopcat, makemime, md5sum, mesg, microcom, mkdir, mkfifo, mkpasswd,
	mktemp, more, mv, nc, nice, nohup, od, patch, pipe_progress, popmaildir, printenv, printf, pscan, pwd, rdate, rdev, readlink, realpath, reformime,
	renice, reset, resize, rev, rm, rmdir, rpm, rpm2cpio, rtcwake, run-parts, runsvdir, rx, script, scriptreplay, sed, sendmail, seq, setconsole,
	setkeycodes, setsid, sh, sha1sum, sha256sum, sha512sum, sleep, softlimit, sort, split, start-stop-daemon, strings, stty, sum, sv, svlogd, sync, tac,
	tail, tar, tcpsvd, tee, telnet, telnetd, test, tftp, tftpd, time, timeout, touch, tr, true, tty, ttysize, udpsvd, uname, uncompress, unexpand, uniq,
	unix2dos, unlzma, unlzop, unxz, unzip, usleep, uudecode, uuencode, vi, watch, wc, wget, which, whoami, whois, xargs, xz, xzcat, yes, zcat

```