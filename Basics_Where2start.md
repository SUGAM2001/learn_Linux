#### Command to display linux system detail
lsb_release -a
#### 1.Start with: pwd, uname, ls, top, atop, htop, mkdir, cd, rmdir, rm, cat touch, wc, head, tail;
```
pwd: Present Working Directory

top: a)PID, b)USER, c)%CPU, d)%MEM, e)TIME, f)COMMAND, g)TASKS, h)Mib Mem, i)MiB Swap 
htop: error
sudo apt install htop.
Error: user is not in list of sudoers
su root 
nano /etc/sudoers
Then add the user below admin user like below syntax.
user_name ALL=(ALL)  ALL
```
#### 2. Let's Find Out: ls -alh, ps aux, clear, ctrl+l, locate, find.
```ls ; ls -a; ls -l; ls -al; ls -alh```

#### 3.   Don't let interest go away: sl,
#### 4.   Do some tricks: history, kill, cp, mv, ssh, scp, rsync, df -h, du, cmp, sudo, apt, snap, chmod, free;
```history
history -set +o turn on
history -set -o turn on
```
