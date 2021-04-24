# Warsztaty Ai/Python HAT UAM
(c) Marcin Machura et al
## Instalowanie pythona
1. Pobierz Anaconda Python i zainstaluj
2. Otwórz Anaconda Command Prompt (konsolę
3. Utwórz środowisko wirtualne:

conda create -n p36 python=3.6

dzięki temu będziemy mieć niezależne kopie pythona i jego bibliotek jakby kolidowały ze sobą
4. Aaktywuj środowisko 
**ważne, trzeba to robic za każydm razem gdy otwieramy nowe okno konsoli**

dla windowsa:`conda activate p36`

dla linuxa/mac:` source activate p36`

5. zainstaluj pakiety
`pip install jupyter jupyterlab numpy pandas matplotlib`
# uruchamianie notatnika
`jupyter notebook`
albo `jupyter lab`

6. Instalacja PyTorch

##### PYTORCH Pro
`conda install -c anaconda mkl`
`conda install -c pytorch pytorch torchvision`


##### PYTORCH nie Pro
`pip install pytorch torchvision`

