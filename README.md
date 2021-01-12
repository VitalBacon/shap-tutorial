# shap-tutorial

Do rozwiązania laboratorium potrzebne będzie przygotowanie odpowiedniego środowiska. Można samemu zainstalować biblioteki z requirements (pamiętając o wersjach, ich zmiana może powodować niekompatybilność). Polecamy jednak skorzystać z virtualenv:

```
virtualenv myenv
source myenv/bin/activate
pip3 install -r requirements.txt
pip3 install ipykernel
python -m ipykernel install --user --name=shap
```

Po takim przygotowaniu jupyter notebook powinien umożliwiać wybór kernela myenv z dostępnymi odpowiednimi bibliotekami.
Późniejsza deinstalacja środowiska:
- usunięcie kernela jupyterowego:
```
jupyter kernelspec remove shap
```
- usunięcie virtualenv (usuwamy folder ze środowiskiem):
```
rm -rf myenv  
```


