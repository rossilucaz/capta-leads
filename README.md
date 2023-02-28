# capta-leads
-Caso de um erro que diz que não tem a biblioteca é só abrir o prompt de comando e colocar
pip install e o nome da biblioteca
Ex: pip install pandas

-Caso de um erro com o chromedriver vc tem que usar o codigo abaixo 

pip install webdriver-manager 

from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager

driver = webdriver.Chrome(ChromeDriverManager().install())


driver_path = '/Users/lucas/Downloads/chromedriver_win32/chromedriver.exe' # AQUI vc coloca o seu path
driver = webdriver.Chrome(driver_path)
