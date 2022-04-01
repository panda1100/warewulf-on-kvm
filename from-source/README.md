```
vagrant plugin install vagrant-libvirt
vagrant up
vagrant ssh server
```

on main

```
cd ~/warewulf
```

on v4.2.0

```
cd ~/warewulf
git checkout tags/v4.2.0 -b v4.2.0
make all
make install
```

on pr

```
cd ~/warewulf
gh auth login # you need a token
gh pr checkout #{pr_id}
```

