.zshrc
```zsh
PATH=~${PATH}:~/local/bin
export PYTHONPATH=~/local/lib/python2.7/site-packages
```

install latest jenkins-job-builder
```sh
git clone https://github.com/openstack-infra/jenkins-job-builder.git
cd jenkins-job-builder
python setup.py install --prefix=~/local
```
