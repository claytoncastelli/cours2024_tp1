# cours-A61
Préparation de la solution d'IA pour la mise en production

Partie-1: https://1drv.ms/f/s!Aprdoflisld-hLt5sJUwc7Njf9k07A?e=V7a6FV

Partie-2: https://1drv.ms/f/s!Aprdoflisld-hLt8-VnDozBPecVR1A?e=qz0v3P

install tox
	pip install tox

generate requerements:
	pip3 freeze > requirements.txt  # Python3
	pip freeze > requirements.txt  # Python2
	
	
create env
source ~/miniconda3/bin/activate
conda init --all

conda create -n tp1_mise_en_prod

Preparing transaction: done
Verifying transaction: done
Executing transaction: done

 To activate this environment, use

     $ conda activate tp1_mise_en_prod

 To deactivate an active environment, use

     $ conda deactivate


