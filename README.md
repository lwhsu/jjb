[Jenkins Job Builder](http://docs.openstack.org/infra/jenkins-job-builder/) config for FreeBSD CI jobs

Install `devel/py-jenkins-job-builder`

`cp jenkins_jobs.ini.sample jenkins_jobs.ini`

Edit `jenkins_jobs.ini` for your credenticals of ci.FreeBSD.org

`make`

=== Install jenkins job builder from source ===

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
