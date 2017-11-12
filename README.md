# DES-UK

Transferring IoA copy of DES data to Cambridge HPCS(https://www.hpc.cam.ac.uk/) CSD3(https://www.csd3.cam.ac.uk/)

rgm@calx066(/data/desardata3/Y3A1){1073}> du -hs
24T

rsync -e ssh -vutrn /data/desardata3/Y3A1/ rm21@login-knl.hpc.cam.ac.uk:/clincloud/des-uk/Y3A1/

login: ssh rm21@login-knl.hpc.cam.ac.uk

On HPCS

[rm21@login-e-5 ~]$ rsync -e ssh -vutrn rgm@muon5.ast.cam.ac.uk:/data/desardata3/Y3A1/ /clincloud/des-uk/Y3A1

login: ssh rm21@login-knl.hpc.cam.ac.uk

cd /clincloud/des-uk/

Installing personal copy of Anaconda
The URL from Contiuum will be something like
wget https://repo.continuum.io/archive/Anaconda2-5.0.1-Linux-x86_64.sh

bash Anaconda2-5.0.1-Linux-x86_64.sh
