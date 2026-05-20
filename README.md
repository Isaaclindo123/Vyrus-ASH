# Vyrus-ASH

Esse executável é um joke virus para trollar seus amigos, se vc quiser colocar outro icone & tirar o aviso, o tutorial está logo abaixo

NAO UTILIZE ISSO EM UM COMPUTADOR DE TRABALHO QUE VC NAO TEM ACESSO A CHAVE DE ADMIN, PFV!!!!!!!!!!

E é isso, divirta-se (:

# Como mudar o ícone e o nome

Para isso, tenha o [PYTHON 3.12 (MSIX)](https://www.python.org/ftp/python/pymanager/python-manager-26.2.msix) E O PYINSTALLER, utilizando: `pip install pyinstaller` e tambem o VyrusAsh.py no mesmo diretorio do icone (baixando o codigo-fonte OU pela aba lançamentos)

E então, coloque esse comando:

```python

python -m PyInstaller --onefile --icon=Nomedoseuiconepersonalizado.ico VyrusAsh.py

```
E depois, é só renomear para o nome que quiser

# Como tirar o aviso

E só tirar isso do VyrusAsh.js:

```javascript

var VBS1 = shell.Run('wscript.exe "vbs1.vbs"', 1, true);

if (VBS1 != 0) {
    WScript.Quit()
}

```
# E é isso, divirta-se (:

Feito por: Eu (:
